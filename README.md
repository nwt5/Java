# Java

This skeleton program must be enhanced as follows:

Your implementation of actionListener will contain your code that responds to button clicks or text entries on the calculator's surface.

You must allow entries using either the keys or by typing text into the expression text field.

The CE button must clear the last operand entered while the C button must clear the entire expression textfield

The equals button must calculate the result and write the resulting value into the result textfield. You must write the evaluation function. We will discuss this in class. Your evaluation must evaluate each operator for it's true precedence. This little bit of logic will take some work!

If the user's expression is gibberish or produced an undefined value like divide by zero - you may write #ERROR# or NaN or any other meaningful indication of a bad expression.

Here is an illustration of how you can extract the operators/operands from an expression String: Tokenize.java
