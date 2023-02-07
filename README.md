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