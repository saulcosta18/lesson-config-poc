Sometimes there are multiple paths a program can take. But you don't want to have to tell your program what to do each time it needs to make a decision!

To automate this process, we use **conditionals**, like the `if` statement. `if` allows you to check that something is `True`, and "if" it is, it does something. Try putting the following code in your program:
```python
if num1 > 1:
    print('Number is greater than 1')
```
This code will print "Number is great than 1." to the terminal, because the `num1` (set at the top of your file) is greater than 1.

This `if` statement contains an **indented block** beneath it, where there are exactly 4 spaces before the start of the `print` statement. Anything that you want to happen if the `if` statement is `True` should be indented 4 spaces as well. 

Let's experiment with `if` statements in your code!

-! Write an if statement to check if the variable num1 is greater than 128. If it is, print "128" to the terminal.
  * requirement: 1
  * negative: Your program should use an `if` statement to compare the variable `num1` to 128.
  * positive: Nice work!
  * xp: python-conditionals:100