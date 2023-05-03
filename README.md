Download Link: https://assignmentchef.com/product/solved-create-a-flowgorithm-to-include-the-usual-comment-lines-for-author-date-and-description
<br>
Create a Flowgorithm program as follows.

Include the usual comment lines for Author, Date and Description.

Declare a Real array for the rainfall amounts, with an array size of 12. Also, declare Real variables for total rainfall (and initialize it to 0), average rainfall, the highest amount of rainfall, and the lowest amount of rainfall.

Declare Integer variables for the array index, the month number of the highest rainfall, and the month number for the lowest rainfall, and initialize the last two to 0.

Create a For loop, with the index from 0 to 11, and inside the loop:

Prompt the user to enter the monthly rainfall amount, and store it in the correct array element. Your prompt should include the month number as 1 to 12 (so you need to display the month number + 1).

Add the amount entered to the total rainfall amount.

If the index is 0, you should set the highest and lowest rainfall amounts to the number entered, so that you have a reference for the other months.

If the amount is greater than the current highest amount, reset the highest amount to the current amount, and set the month of highest rainfall to the current index. Likewise, if the amount is lower than the current lowest amount, reset the new lowest amount, and set the month of the lowest rainfall to the current index.

When the loop exits, compute the average by dividing the total rainfall amount by 12. Then display the total and average rainfall, the month number with the highest rainfall and that amount, and the month number with the lowest and that amount. NOTE: You do not have to NAME the months; the number of the months will do.

Run the program. The program should ask you to enter the amount of rainfall for 12 months. Then it displays the total and average rainfall, the highest month and its amount, and the lowest month and its amount. If there are any errors, recheck the instructions and correct them, then resave the file.

The screen shot below shows the last part of the Console window when the program was run with the amounts 30, 25, 20, 15, 10, 5, 60, 55, 50, 45, 40, 35. (Note that the index values were increased by 1 when displaying month numbers to the user.)

Save the program as S09.fprg.