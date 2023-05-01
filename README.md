Download Link: https://assignmentchef.com/product/solved-calculate-the-factorial-of-a-number
<br>
In this exercise, you’ll create a form that accepts an integer from the user and then calculates the factorial of that integer.

Reminder: The factorial of an integer is that integer multiplied by every positive integer less than itself. A factorial number is identified by an exclamation point following the number. Here’s how you calculate the factorial of the numbers 1 through 5: 1! = 1 which equals 1 2! = 2 * 1 which equals 2 3! = 3 * 2 * 1 which equals 6 4! = 4 * 3 * 2 * 1 which equals 24 5! = 5 * 4 * 3 * 2 * 1 which equals 120 To be able to store the large integer values for the factorial, this application can’t use the Int32 data type.

1. Start a new project named Factorial in the Assignmnet3Ex1_Factorial directory.

2. Add labels, text boxes, and buttons to the default form and set the properties of the form and its controls so they appear as shown above. When the user presses the Enter key, the Click event of the Calculate button should fire. When the user presses the Esc key, the Click event of the Exit button should fire.

3. Create an event handler for the Click event of the Calculate button. a. This event handler should get the number the user enters, b. calculate the factorial of that number (you will use for or while loop), c. display the factorial with commas but no decimal places (think of formatting), d. and move the focus to the Number text box. e. It should return an accurate value for integers from 1 to 20. (The factorial of the number 20 is shown in the form above.)

4. Create an event handler for the Click event of the Exit button that closes the form.

5. Test the application to be sure it works correctly.