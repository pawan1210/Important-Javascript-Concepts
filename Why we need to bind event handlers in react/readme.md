### Why we need to bind event handlers in react
https://www.freecodecamp.org/news/this-is-why-we-need-to-bind-event-handlers-in-class-components-in-react-f7ea1a6f93eb/

#### If we use inline event handlers then there's no need of any binding.
```
this.state = { inputText: "xyz" }

<input 
  type="text" 
  value={ this.state.inputText }
  onChange={(e)=> { 
  this.setState({ inputText:e.target.value }) 
  }} 
/> 

```
