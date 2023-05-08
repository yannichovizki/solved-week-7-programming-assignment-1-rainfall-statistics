Download Link: https://assignmentchef.com/product/solved-week-7-programming-assignment-1-rainfall-statistics
<br>
<p class="title">This program will be a modification of the program done in CISS 241, Week 7 Programming Assignment 1. That was the Rainfall Statistics program. For those who did not take 241, that program description is below. Modify the Rainfall Statistics program so that it displays a list of months, sorted in the order of rainfall from highest to lowest.

5/5 - (3 votes)




Write a program that lets the user enter the total rainfall for each of 12 months into an array of doubles. The program should use two 12 element arrays. One array will hold strings, the names of the 12 months. This array will be initialized when the array is created using an initialization list (could also be created as a array of constants). The second array will hold doubles which will be the total rainfall for each month. The program will prompt the user for the rainfall for each month (using both arrays) and store the value entered into the array with the rainfall totals, the other is used to display which month the program is asking for the rainfall total. The program should display the following once the data is all entered:

<ul>

 <li>The total rainfall for the year</li>

 <li>The average monthly rainfall</li>

 <li>The month with the highest amount of rainfall (must display the month as a string)</li>

 <li>The month with the lowest amount of rainfall (must display the month as a string)</li>

</ul>

The program must have the following functions:

<ul>

 <li>double getTotal(double [ ], int);</li>

 <li>double getAverage(double [ ], int);</li>

 <li>double getLowest(double [ ], int, int&amp;); //returns the lowest value, provides the index of the lowest value in the last parameter.</li>

 <li>double getHighest(double [ ], int, int&amp;); //returns the highest value, provides the index of the highest value in the last parameter</li>