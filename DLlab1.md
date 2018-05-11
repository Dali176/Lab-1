# 2 Things I Learned in the Form of Quiz Questions

1. Is the following code synchronous or asynchronous?

```js
var food = fs.readFile('food.txt', 'utf8', function(err, food) {
  if (err) {
    console.log(err);
  } else {
    console.log(food);
  }
}};
```

## Answer: asynchronous because it uses a callack function
