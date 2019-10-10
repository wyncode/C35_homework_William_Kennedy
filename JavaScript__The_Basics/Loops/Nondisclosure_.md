Download some JavaScript code using the following command.

```bash

Input: curl -sL http://bit.ly/2HGDKF5 > script.js # Type your command.

Output: # Nothing will be output to the screen.

Explanation: A gist is downloaded into a file named `script.js`.

```

Examine the code in your text editor.

```bash

Input: <atom or your editor of choice> script.js # Type your command.

Output: # Nothing. The file should open in your editor.


```

Then execute the script using `node`.

```bash

Input: node script.js # Type your command to run the script

Output: # The output should look something like this: http://bit.ly/2LDSyqz


```

Explain the difference in output in the following code that contains 2 for loops, one with a `var` variable declaration and definition and another with a `let` varaible declaration and definition.

Why do the closures with `var i` output 10 each time the closure is called and the closures with `let i` output 0 to 9?