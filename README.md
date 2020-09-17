## COSC 499 Test Project

This is a small test project.

### Running the Program
To run the program, simply open the `index.html` file in your browser.
There are instructions on how to use the program built into the program itself.

### Features
* A number game. Input numbers until you guess the one the computer thinks of.
* Input Validation. Input is checked locally for validity.
* Looks nice. CSS is applied to spice things up a bit.
* Responsive design. Looks nice on a small browser window or phone.

### About Testing
I added one test for my code, to test the only function that has both input and output in this program, the isValidInput function.
This function is supposed to accept one argument, and tests if this is a number, an integer, and that is in the specified range.
To run this test, click on the "Test me!" button on the bottom of the document.

I thought about making the random number generator a function, but since it is precisely that and it's output value is unknown, the only thing we could test is that it returns an integer.
