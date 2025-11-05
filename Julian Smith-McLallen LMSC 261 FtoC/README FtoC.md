#FtoC process and completion
Began by creating a prompt for the user to enter their "F" variable

Borrowed the const command from the area of a circle example in the codealong

Line 2:
const C = (F - 32 * 5 / 9)

The operations in the parentheses were written incorrectly and the results were wildly inaccurate

Put the 5/9 in an extra pair of parentheses, results were closer but still not correct

Put -32 in parantheses and the code successfully put out the temperature in Celsius

Line 3:
console.log("The temperature is", C)