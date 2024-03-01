## Task1
1. Prepare the sample csv file for car model and their specification, the column names would be  
a. Company Name 
b. Model Name 
c. Fuel Type (For e.g. Petrol, Gas, Diesel, EV) 
d. Body Style (for e.g. Hatchback, Sedan, SUV) 
e. Car Length 
2. Prepare the sample excel file for the car prizing  and loan amount, the column names would be 
a. Company Name 
b. Model Name 
c. On road pricing 
d. Loan amount 
e. Monthly EMI 
f. Interest Rate 
g. Monthly Principal 
h. Monthly Interest 
3. Write the code to read the csv file and the excel file and convert them into the Data frame. 
4. Merge the two Data frame on the basis of primary key 
5. Fill the “NA” values in the merged data frame 
6. Iterate over the merged Data frame and add the GST value in the “On road pricing” column

##  Task 2 
 
1. Prepare the Titanic dataset file (download it from Google) 
2. Find out the names of passengers younger than 35 years. 3. Print the rows from index 10 to 25 and columns 3 to 5 
4. Find out the statistics aggregate of Age & Fare using the DataFrame.agg() method 
5. Find out the mean ticket fare price for each of the sex and cabin class combinations

## Task 3

Write a Python script using the openpyxl library to read data from an Excel spreadsheet, manipulate the data, and write the results back to a new spreadsheet.  
The Excel spreadsheet should have the following format:  
1. The data should be in a table with a header row and at least one row of data.
2. The first column should contain the name of a fruit, and the second column should contain the quantity of that fruit.
The script should perform the following tasks:
1. Read the data from the Excel spreadsheet.
2. Calculate the total quantity of each fruit.
3. Write the results to a new Excel spreadsheet with the following format:
4. The first column should contain the name of each fruit.
5. The second column should contain the total quantity of that fruit.

## Task 4
Write a Python program using NumPy to perform the following tasks on a given array: 
1. Create a NumPy array with the following values: [1, 2, 3, 4, 5]. 
2. Print the shape of the array using the .shape attribute. 
3. Reshape the array into a 2D array with 2 rows and 3 columns. 
4. Print the shape of the new array. 
5. Create a second NumPy array with the following values: [6, 7, 8, 9, 10]. 
6. Concatenate the two arrays together horizontally. 
7. Print the resulting array. 
8. Compute the resulting array's mean, median, and standard deviation.

## Task 5
1. Write a Python code to Create a figure with 2x2 subplots. 2. In the first subplot (top-left), plot a bar chart using the following data: 
Categories: ['Category A', 'Category B', 'Category C', 'Category D', 'Category E'] 
Values: [23, 56, 41, 62, 19] 
3. In the second subplot (top-right), plot a histogram using the following data: 
Data: [12, 17, 21, 18, 14, 13, 16, 9, 12, 15, 19, 11, 14, 16, 20, 18, 15, 13, 16, 11, 10] 
4. In the third subplot (bottom-left), plot a pie chart using the following data: 
Labels: ['Apple', 'Banana', 'Orange', 'Mango'] 
Sizes: [30, 25, 15, 30] 
5. In the fourth subplot (bottom-right), plot a scatter plot using the following data: 
X values: [1, 2, 3, 4, 5] 
Y values: [2, 5, 3, 6, 4] 
6. Add appropriate titles and labels to each subplot. 7. Adjust the spacing between subplots to avoid overlapping. 
