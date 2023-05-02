Download Link: https://assignmentchef.com/product/solved-cmi-assignment-6-file-i-o-and-floating-point-numbers
<br>
<strong>File I/O and Floating-Point Numbers</strong>

Write an ARMv8 assembly language program to compute the function ln(<em>x</em>) using the series expansion shown below. Use double precision floating-point numbers. The program will read a series of input values from a file whose name is specified at the command line. The input values will be in binary format; each number will be double precision (and thus each is 8 bytes long). Read from the file using system I/O (i.e. generate an exception using the <em>svc</em> instruction). Process the input values one at a time using a loop (be sure to detect end-of-file correctly), calculate ln(<em>x</em>), and then use printf() to print out the input value and its corresponding output values in table form (i.e. in columns, with column headings) to the screen (standard output). Print out all values with a precision of 10 decimal digits to the right of the decimal point.




You can compute the function ln(<em>x</em>) according to the following series expansion:













where <em>x</em> is a real number input to the function and <em>x</em> &gt; 1/2. Continue to accumulate terms in the series until the absolute value of the term is less than 1.0e-13.




Run your program using the input binary file supplied on D2L. Capture its execution using the <em>script </em>UNIX command, and name the output file <em>script.txt</em>.




N<strong>ew Skills need for this Assignment:</strong>




<ul>

 <li>Use of system I/O (exceptions) to open and read an input binary file</li>

 <li>Understanding and use of floating-point single and double formats</li>

 <li>Use of floating-point instructions to do simple calculations</li>

 <li>Use of floating-point comparison instructions</li>

</ul>


