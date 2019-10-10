Copy the code below into a new file, and let's look it over:

```js
let beatles = [
  {
    name: null,
    nickname: "The Smart One"
  },
  {
    name: null,
    nickname: "The Funny One"
  },
  {
    name: null,
    nickname: "The Cute One"
    },
  {
    name: null,
    nickname: "The Quiet One"
  }
];

beatles.forEach( beatle => {
   // Your code goes here
}) ;

beatles.forEach( beatle => {
  console.log( "Hi, I'm " + beatle.name + ".  I'm " + beatle.nickname + "!" );
});
```

The first line is one way to represent the Beatles. This data structure is an `Array` of `Objects`.

Next, we see a loop iterating each of the elements in the beatles array. We want it to loop through all of them and match their names to their nicknames, using a _Switch_ statement. Add your code inside to accomplish this. If you don't know their nicknames, **Google it**.

Finally, the last bit of code loops through the array once again and prints the result on screen. Submit the entire contents of the file when you're finished.

Note: You only need their first name!