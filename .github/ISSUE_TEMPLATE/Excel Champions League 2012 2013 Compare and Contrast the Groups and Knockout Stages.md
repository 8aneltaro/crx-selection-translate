
 
# How to use Excel to track UEFA Champions League 2012/13
 
If you are a fan of European football, you might want to keep track of the UEFA Champions League 2012/13, the most prestigious club competition in the continent. Excel can help you do that with some simple formulas and functions. Here are some steps to create your own spreadsheet for the tournament.
 
1. Download the official match calendar from [UEFA.com](https://www.uefa.com/uefachampionsleague/history/seasons/2013/) and save it as a CSV file.
2. Open a new workbook in Excel and import the CSV file as a table. You can use the Data tab and click on From Text/CSV.
3. Format the table as you like, such as adjusting the column widths, applying filters, and adding conditional formatting.
4. Add a new worksheet and name it Groups. In this sheet, you will create a table for each group of four teams that shows their standings based on points, goal difference, and goals scored.
5. In cell A1, enter Group A. In cell A2, enter Team. In cell B2, enter Pts (points). In cell C2, enter GD (goal difference). In cell D2, enter GS (goals scored).
6. In cells A3:A6, enter the names of the teams in Group A: Porto, Dynamo Kyiv, Paris Saint-Germain, and Dinamo Zagreb.
7. In cell B3, enter this formula: =SUMIFS('Match Calendar'!$H:$H,'Match Calendar'!$C:$C,A3)+SUMIFS('Match Calendar'!$H:$H,'Match Calendar'!$F:$F,A3). This will calculate the total points for Porto based on the results in the Match Calendar sheet.
8. Copy and paste this formula down to cells B4:B6 for the other teams in Group A.
9. In cell C3, enter this formula: =SUMIFS('Match Calendar'!$G:$G,'Match Calendar'!$C:$C,A3)-SUMIFS('Match Calendar'!$I:$I,'Match Calendar'!$C:$C,A3)+SUMIFS('Match Calendar'!$I:$I,'Match Calendar'!$F:$F,A3)-SUMIFS('Match Calendar'!$G:$G,'Match Calendar'!$F:$F,A3). This will calculate the goal difference for Porto based on the goals scored and conceded in the Match Calendar sheet.
10. Copy and paste this formula down to cells C4:C6 for the other teams in Group A.
11. In cell D3, enter this formula: =SUMIFS('Match Calendar'!$G:$G,'Match Calendar'!$C:$C,A3)+SUMIFS('Match Calendar'!$I:$I,'Match Calendar'!$F:$F,A3). This will calculate the goals scored for Porto based on the Match Calendar sheet.
12. Copy and paste this formula down to cells D4:D6 for the other teams in Group A.
13. Select cells A2:D6 and sort them by column B (points), then by column C (goal difference), then by column D (goals scored), in descending order. This will rank the teams according to their standings in Group A.
14. Repeat steps 5-13 for the other groups (B to H) by changing the group name in cell A1 and the team names in cells A3:A6 accordingly.
15. You can also add some charts or sparklines to visualize the performance of each team or group.

Now you have a spreadsheet that can help you follow the UEFA Champions League 2012/13 with Excel. You can update it after each match day by entering the scores in the Match Calendar sheet. Enjoy!
 
**Download Zip ››› [https://corppresinro.blogspot.com/?d=2uFy08](https://corppresinro.blogspot.com/?d=2uFy08)**


 8cf37b1e13
 
