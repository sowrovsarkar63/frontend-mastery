# JavaScript Arrays

[JavaScript Arrays](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays) are generally described as list-like objects, in that they're essentially a list of various differing types of data.

In your console, Arrays can be seen as comma-separated values contained within a set of square brackets. Below is an example of a JavaScript array.

```js
[1, null, "Welcome to FrontEnd Mastery!", true]
```

In JavaScript, there are a large variety of methods you can use to modify your arrays.

For example, let's take the above array. If we wanted to add something to the very end of the array, we would use .push(). Let's take a glimpse as to how this would look.

```js
const myArr = [1, null, "Welcome to FrontEnd Mastery!", true];
myArr.push("Arrays are easy!");

// This will return the following
// [1, null, "Welcome to FrontEnd Mastery!", true, "Arrays are easy!"]
```

Similarly to this, we can also use .unshift() to place items into the beginning of an array.

If we wanted to access a specific entry of our array, we would use square brackets to look up the value of a particular index in the array. Take a look at the example below.

```js
const myArr = [1, null, "Welcome to FrontEnd Mastery!", true];
myArr[2];

// This will return the following
// ["Welcome to FrontEnd Mastery!"]
```

It's important to note that in JavaScript, like in many other programming languages, we typically start counting from zero. So the first element in an array is ACTUALLY the zero-th element, and so on. It's a bit confusing at first, but you'll get the hang of it eventually.
