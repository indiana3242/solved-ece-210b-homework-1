Download Link: https://assignmentchef.com/product/solved-ece-210b-homework-1
<br>
In this assignment, you will utilize the basic skills you learned in the first week of class; you will assign values to variables, use some of MATLAB’s basic functions, and perform some simple arithmetic operations on scalars and matrices. You should also use this assignment as a way to get comfortable with the <em>help </em>and <em>doc </em>functions. For your final submission, as always, please suppress all outputs with semicolons. Separate each question into separate sections. It may be good to get into the habit of beginning your scripts with <em>clc</em>, <em>clear </em>and <em>close all</em>. Don’t remember what these do? Use <em>help</em>!

<ol>

 <li>Create scalar variables with the following values:</li>

</ol>

Give these variables unique and reasonable names. Using these variables (not the expressions) create a column vector with each variable as an entry.

<ol start="2">

 <li>You should have two complex variables from the previous question. Multiply thetwo together (using the variables again) and save that as a variable. Compute the real part, imaginary part, magnitude and angle of the resulting complex number and create a row vector using those values as entries.</li>

 <li>Now with the two vectors from the previous questions, create and save as variablestwo 4×4 matrices as follows:

  <ul>

   <li>Regular matrix multiplication (make sure the vectors are in the right order! I want a 4×4 matrix, not a scalar, i.e. an outer product, not an inner product)</li>

   <li>Transpose (regular transpose not conjugate transpose) the column vector and multiply it elementwise with the row vector. Then use <em>repmat </em>to extend this row vector to a 4×4 matrix (use <em>help </em>or <em>doc </em>if you don’t remember how to use <em>repmat</em>).</li>

  </ul></li>

 <li>With these two matrices, perform the following operations (save the results as variables):

  <ul>

   <li>Add the first and two times the second</li>

   <li>Elementwise multiply them</li>

   <li>Subtract two from every entry in the first matrix</li>

   <li>Conjugate transpose either one</li>

  </ul></li>

</ol>

1

ECE-210B Homework 1

<ol start="5">

 <li>Take the angle of the complex number in question 2 and convert it to degrees (checkout <em>rad2deg</em>). It should be an integer. Save the value as <em>n</em>. Then create these two row vectors:

  <ul>

   <li>A length 2000 vector with equally spaced entries from 1 to <em>n</em></li>

   <li>A vector with entries starting at one up to <em>n </em>with entries spaced at intervals of 0.3 (the vector may turn out to not include <em>n</em>)</li>

  </ul></li>

</ol>

You will be using both <em>linspace </em>and the colon operator here. Make sure to use the right one for each!


