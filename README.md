Download Link: https://assignmentchef.com/product/solved-cs161-week-2
<br>
Write a program that asks the user for five numbers and then prints out the average of those numbers.  When you run your program, it should match the following format:

Please enter five numbers.

-2.4

5.1

6.0

123.8 -19.0

The average of those numbers is:

22.7

The file must be named: ​<strong>average.cpp</strong>​.  To compile it into an executable file named

“average”, enter “g++ average.cpp -o average”.  “g++” is the name of the compiler, “average.cpp” is the name of your program, “-o average” says that you want the executable file to be named “average” (you do not have to match the name of your .cpp file).  If you don’t use the -o option, then the executable file will be named “a.out”.




<h1>Project 2.b</h1>

Write a program that converts Celsius temperatures to Fahrenheit temperatures.  The formula is: F=9/5C+32

where F is the Fahrenheit temperature and C is the Celsius temperature.  The program should prompt the user to input a Celsius temperature and should display the corresponding Fahrenheit temperature.  It should display ​<strong>only</strong>​ the converted temperature without any text (not even a ‘F’).  When you run your program, it should match the following format:

Please enter a Celsius temperature.

-10.5

The equivalent Fahrenheit temperature is:

13.1

The file must be named ​<strong>tempConvert.cpp</strong>​.




<h1>Project 2.c</h1>

Write a program that asks the user for a (integer) number of cents, from 0 to 99, and outputs how many of each type of coin would represent that amount with the fewest total number of coins.  When you run your program, it should match the following format:

Please enter an amount in cents less than a dollar.

87

Your change will be:

Q: 3 D: 1 N: 0 P: 2

Hint: You will find the mod operator (%) and integer division useful.

The file must be named: ​<strong>change.cpp</strong>​.