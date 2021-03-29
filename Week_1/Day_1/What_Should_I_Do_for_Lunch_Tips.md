### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```js
const whatToDoForLunch = function (hungry, availableTime) {
  if (hungry === false) {
    console.log(`I'm not hungry, and will back to work.`);
  } else if (hungry === true && availableTime <= 20) {
    console.log(`I'm hungry, but we've got only ${availableTime} mins, we should eat it in the lab.`);
  } else if (hungry === true && availableTime > 20 && availableTime <= 30) {
    console.log(`I m hungry, and we've got ${availableTime} mins, we can try a place nearby.`);
  } else {
    console.log(
      `I am hungry, and we've got ${availableTime} mins available, but we're in the bootcamp, we should only spare 30 mins for lunch. `
    );
  }
};
```

