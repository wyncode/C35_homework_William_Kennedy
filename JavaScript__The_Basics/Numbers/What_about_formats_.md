We created a tip calculator and our result gave us a lucky float (`33.75`) but what happens when the amount is even, like `33`? Since we are dealing with money now we are expected to express our result in a specific way like this: `$33.00` Let's revisit our tip calculator with some different data: 

```js 
let billTotal = 675; 
let partySize = 1; 
let tipPercentage = 20; 
``` 

Using your code for the tip calculator, add the necessary **TEXT FORMATTING** to your output so it reflects that we're dealing with currency. Take a look at the documentation [HERE](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number/toLocaleString#Using_options) to correctly format currency.