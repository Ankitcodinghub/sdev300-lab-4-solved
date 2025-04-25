# sdev300-lab-4-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/sdev300-week-4-deliverables-solved-2/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;128233&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;SDEV300 Lab 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
<div class="kksr-stars">
    
<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
    
<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>
                

<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Overview: In this week, you have studied additional Python language syntax including Arrays and Strings. In particular, you used the numpy, regular expressions, and Panda libraries to help manipulate and store data. The Lab for this week demonstrates your knowledge of this additional Python functionality. Be sure to use the examples in the textbook reading along with the associate libraries, functions and processes when completing the assignments for this week.

Submission requirements for this project include 2 files. (Zipping them into one file is acceptable and encouraged):

• Python Numpy and Pandas Application Code

• Word or PDF file containing your test and pylint results

Python Applications for this lab: (total 100 points):

This lab consists of two parts.

1. (80 points) allows a user to enter and validate their phone number and zipcode+4. Then the user will enter values of two, 3×3 matrices and then select from options including, addition, subtraction, matrix multiplication, and element by element multiplication. You should use numpy.matmul() for matrix multiplication (e.g. np.matmul(a, b) ). The program should compute the appropriate results and return the results, the transpose of the results, the mean of the rows for the results, and the mean of the columns for the results.

When entering data, the application should use regular expressions and/or Pandas functionality to check the format of the phone number and zipcode. You should check that each value is numeric for the matrices. The user interface should continue to run until the user indicates they are ready to exit.

A user interface might look similar to this:

***************** Welcome to the Python Matrix Application***********

Do you want to play the Matrix Game?

Enter Y for Yes or N for No:

Y

Enter your phone number (XXX-XXX-XXXX:

555-555-55

Your phone number is not in correct format. Please renter:

555-555-5555

Enter your zip code+4 (XXXXX-XXXX):

21022-3213

Enter your first 3×3 matrix:

1 2 4

4 2 1

3 8 9

Your first 3×3 matrix is:

1 2 4

4 2 1

3 8 9

Enter your second 3×3 matrix:

3 2 1

7 2 5

5 2 1

Your first 3×3 matrix is:

3 2 1

7 2 5

5 2 1

Select a Matrix Operation from the list below:

a. Addition

b. Subtraction

c. Matrix Multiplication

d. Element by element multiplication a

You selected Addition. The results are:

4 4 5

11 4 6

8 10 10 The Transpose is:

4 11 8

4 4 10

5 6 10

The row and column mean values of the results are:

Row: 4.33, 7, 9.33 Column: 7.66, 6, 7

Do you want to play the Matrix Game?

Enter Y for Yes or N for No:

N

*********** Thanks for playing Python Numpy ***************

If an inappropriate entry is detected, the program should prompt for a correct value and continue to do so until a correct value is entered.

Hints:

1. Use numpy, pandas and regular expressions as appropriate.

2. Create and use functions as often as possible

3. Use comments to document your code

4. Both integers and float values are acceptable 5. Use comments to document your code

6. Test with many combinations.

7. Use pylint to verify the code style – the goal is a 10!

2. (20 points) Document your testing results using your programming environment. You should also include and discuss your pylint results for the application. The test document should include a test table that includes the input values, the expected results and the actual results. A screen capture should be included that shows the actual test results of running each test case found in the test table. Be sure to include multiple test cases to provide full coverage for all code and for each function you develop and test.
