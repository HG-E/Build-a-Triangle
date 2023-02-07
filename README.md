Directions:
For this quiz, you're going to create a function called buildTriangle() that will accept an input (the triangle at its widest width) and will return the string representation of a triangle. See the example output below.

buildTriangle(10);
Returns:

* 
* * 
* * * 
* * * * 
* * * * * 
* * * * * * 
* * * * * * * 
* * * * * * * * 
* * * * * * * * * 
* * * * * * * * * * 
We've given you one function makeLine() to start with. The function takes in a line length, and builds a line of asterisks and returns the line with a newline character.

function makeLine(length) {
  var let = "";
  for (let j = 1; j <= length; j++) {
    line += "* "
  }
  return line + "\n";
}
You will need to call this makeLine() function in buildTriangle().

Think It Through!
This will be the most complicated program you've written yet, so take some time thinking through the problem before diving into the code. What tools will you need from your JavaScript tool belt? Professionals plan out their code before writing anything. Think through the steps your code will need to take and write them down in order. Then go through your list and convert each step into actual code. Good luck!

Running Your Code


This code creates a triangle made of asterisks (*) by defining two functions: makeLine and buildTriangle.

The makeLine function takes one argument length and returns a string of asterisks (*) that is length characters long. For example, if length is 4, then makeLine(4) returns the string "* * * * \n".

The buildTriangle function takes one argument length and returns a string that represents a triangle made of asterisks. It does this by using the makeLine function and concatenating the strings returned by makeLine one by one to form a triangle shape. For each line of the triangle, the length of the string returned by makeLine increases by 1, until it reaches length.

The code then calls buildTriangle(10) and logs the result to the console. This will create a triangle made of asterisks with 10 lines, and each line will have one more asterisk than the previous one.
Enter the following in the terminal:

node triangle.js
Testing Your Code
Change the parameter in the testing code to confirm that your program works for different values of length.

console.log(buildTriangle(3));
should log out:

* 
* * 
* * * 
console.log(buildTriangle(6));
should log out:

* 
* * 
* * * 
* * * * 
* * * * * 
* * * * * * 
and

console.log(buildTriangle(10));
should log out

* 
* * 
* * * 
* * * * 
* * * * * 
* * * * * * 
* * * * * * * 
* * * * * * * * 
* * * * * * * * * 
* * * * * * * * * * 


NOTE:
This code creates a triangle made of asterisks (*) by defining two functions: makeLine and buildTriangle.

The makeLine function takes one argument length and returns a string of asterisks (*) that is length characters long. For example, if length is 4, then makeLine(4) returns the string "* * * * \n".

The buildTriangle function takes one argument length and returns a string that represents a triangle made of asterisks. It does this by using the makeLine function and concatenating the strings returned by makeLine one by one to form a triangle shape. For each line of the triangle, the length of the string returned by makeLine increases by 1, until it reaches length.

The code then calls buildTriangle(10) and logs the result to the console. This will create a triangle made of asterisks with 10 lines, and each line will have one more asterisk than the previous one.
