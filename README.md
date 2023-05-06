Download Link: https://assignmentchef.com/product/solved-eecs3020-homework-2-cyclic-redundancy-check-crc
<br>
<strong>Cyclic Redundancy Check (CRC) </strong>

In this homework, you are asked to write a MATLAB program for the cyclic redundancy check (CRC) code, using CRC-32. Please download the data M(x) (inputdata.mat that contains a binary vector of 12000bits named “packet”) on eLearn.

<ol>

 <li>Use the inputdata M(x) and the generator of CRC-32</li>

</ol>

<em>C</em>(<em>x</em>)<em>x</em>32<em>x</em>26<em>x</em>23<em>x</em>22<em>x</em>16<em>x</em>12<em>x</em>11

<h1><em>x</em><sup>10</sup><em>x</em><sup>8</sup><em>x</em><sup>7 </sup><em>x</em><sup>5</sup><em>x</em><sup>4</sup><em>x</em><sup>2</sup><em>x</em>1</h1>

to find the transmitted message P(x) (as a binary vector of 12032 bits). (Note: Do not use the function of CRC32 in MATLAB.)

<ol start="2">

 <li>Suppose that you are a middle man and you would like to corrupt the transmitted message P(x) by adding an undetectable error E(x) into P(x). A trivial way to do this is to let E(x)=C(x) and add C(x) to P(x). But this will change 15 bits in P(x) as there are 15 nonzero terms in C(x). Can you find an E(x) that only needs to change at most 10 bits in P(x)? Your score for this problem will depend on the number of bits that you need to change in P(x).</li>

</ol>




<u>Upload a compressed files (YourID.rar, e.g., 99064599.rar) that contents your results as two binary arrays P(x) and E(x)</u><u> in a file (YourID.mat, e.g.,</u> <u>99064599.mat) that contains two binary vectors of 12032bits named </u>

<u>“codepacket” (P(x)) and “error”( E(x) ) and the two source code files (YourID_1.m,  e.g., 99064599_1.m for generating P(x) and YourID_2.m,</u> <u>e.g., 99064599_2.m for generating E(x)) to eLearn.</u>


