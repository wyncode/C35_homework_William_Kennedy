Now that we have some basic building blocks. We can put them together into larger more complex structures.
Define a function called `maxNumber` that has two parameters. We're going to _assume_ that the parameters values can only be numbers. Using your knowledge of boolean logic and control flow, write the necessary code to make the function **return** the number with the highest value.
Finally, test your function with this code:

```js
function testMaxNumber(){
  console.log( maxNumber( 10, 0 ) === 10 );
  console.log( maxNumber( -21, -4 ) === -4 );
  console.log( maxNumber( 23, 27 ) === 27 ) ;
}

testMaxNumber();
```
Your tests should output:

```shell
true
true
true
```