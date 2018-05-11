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

## Answer: Asynchronous because it uses a callback function

2. Is the following code synchronous or asynchronous?

```js
function abc()
{
   console.log('abc');
}


function xyz()
{
   abc()
   console.log('xyz');
}
var one = 1;
xyz();
```

## Answer: Synchronous because it has to go in order, and isn't parallel

# 2 Questions I still have are...

* Why are we learning JS? The language is outdated in modern web.
* Will this just be basic JS or will it be useful for todays use?

! [Image of -v](https://github.com/Dali176/Lab-1/blob/master/images/Screenshot%20(34).png)
