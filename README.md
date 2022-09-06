# RPA_Bot
1. Read the data from the following URL and save it into data table variable
https://rpademo.automationanywhere.com/itbricks_enroll.php
2. Create excel sheet using excel advanced package
3. Write the data table into the created sheet
4. Insert new column (will be in G column)
5. Set cell in created column (in G column) and put the value “Status”
6. Loop through the data in the excel sheet and assign each column into variable
7. Create a number variable and assign value 2 to it to use it as counter variable
8. Open the following URL
https://rpademo.automationanywhere.com/itbricks_crm.php
9. Write each value in its specific text box (ex: first name in first name text box, … etc)
10. After clicking on button “Register”, update the column G with value “Done”
a. Hint: use action “set cell” and choose “specific cell” and put the column name “G”
following by the created number variable.
b. Ex: G$counter.Number:toString$
11. After clicking on “Clear Form”, increment the counter
12. After inserting all data into the form, send to me the updated excel sheet using email package.
