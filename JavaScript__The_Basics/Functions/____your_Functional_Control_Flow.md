So we can get the max of two numbers now. But what if we need to find the highest value in any number of arguments?
Please re-write the `maxNumber` function from the previous exercise to work with **any**  number of arguments.
After you're done, test it with this code:

```js
function testMaxNumber(){
  console.log( maxNumber( 10, 0, 20, 3, 19 ) === 20 );
  console.log( maxNumber( -21, -4, -109, -1 ) === -1 );
  console.log( maxNumber( 27 ) === 27 ) ;
}
 
testMaxNumber();
```
This is supposed to be a bit more challenging.  