### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
const whatToDoForLunch = function (hungry, availableTime) {
  if (hungry === true) {
    if (availableTime <= 19) {
      console.log('pick something up and eat in back in the Lab or in the kitchen, where you can get to know your fellow classmates');
    }
    else if (availableTime <= 20) {
      console.log('you deserve a break and could try a place in Gastown.');
    } else if (availableTime >= 30) {
      console.log('this is a bootcamp after all and you should probably reconsider.');
    }
  }
  else {
    console.log('Get back to work.');
  }

}
```