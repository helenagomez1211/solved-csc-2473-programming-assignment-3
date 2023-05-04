Download Link: https://assignmentchef.com/product/solved-csc-2473-programming-assignment-3
<br>
<strong>CSC 2473</strong>

<strong>Programming Assignment</strong>

<hr>




<ol>

 <li>There are two programming assignments for this chapter. Be sure to refer to the “Green Sheet” for guidance for preparing the programs.</li>

 <li>The first programming assignment is to write a program as indicated in Programming Problem 1 on page 133 in the textbook. Compute the volume for 3 cones using the values indicated below. The output will be formatted as shown below:</li>

</ol>

<pre><code>        Radius     Height      VolumeCone 1     10.10      20.10     Cone 2     40.20      60.20   Cone 3     80.30      90.30   </code></pre>

Declare Pi with the value 3.1416 as a constant (type double) above the main function in your program. Set the precision of all floating point output to 2 decimal positions.

<ol start="3">

 <li>Following is information related to the second program in this assignment. Dilbert wants to buy a car. The loan company will charge him an annual interest rate of 9% for a loan. His payments will be 165.25 each month for 36 months. He wants to know what the balance will be after he makes the first payment, after the second payment and after the third payment. He knows that you are a computer programmer and solicits your assistance.</li>

</ol>

The formula for computing the remaining balances is:

<pre><code>baIN = Payment * (1 - pow(1 + Monintrate, N - Totnum)) / Monintrate</code></pre>

(This formula will be used 3 times with different values for N.)

where

Your program will output the basic information related to the loan (monthyl payments, annual interest rate, and total number of payments). It will also output the balance remaining after the first, second, and third payments. The balances will be shown in dollars and cents.

<ol start="4">

 <li>Below are some helpful hints for writing the second program:</li>

</ol>

<ul>

 <li>Include cmath and iomanip header files in your include statements.</li>

 <li>Declare monthyl interest rate, number of payments, and payment amount as constants.</li>

 <li>Declare balance and payment number as variables.</li>

 <li>Use setprecision to control the number of decimal positions displayed.</li>

 <li>If you need to clear the screen use <code>system ("cls"); //(requires #include cstdlib)</code></li>

 <li>Take some time to think about the program requirements before rushing to write the program. Make sure you understand the requirements before proceeding. If some part of it is not clear, please talk to me.</li>

 <li>The balance after the first payment is $5070.31. I give you this value so you will have something to confirm you have written the formula correctly.</li>

</ul>

5/5 - (1 vote)