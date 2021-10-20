### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  switch(hungry){
    case false:
      console.log("get back to work!");
      break;
    case true && availableTime < 20:
      console.log("Pick something up and eat in the lab")
      break;
    case true && availableTime >= 20 && availableTime <= 30:
      console.log("try nearby place")
      break;
    default:
      console.log("how much time do I have left?")
  }
}
```