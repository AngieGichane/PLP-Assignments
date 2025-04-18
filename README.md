# PLP-Assignments

# Python Week 1 Assignment
Basic Calculator Program 

1. Create a simple Python program that asks the user to input two numbers and a mathematical operation (addition, subtraction, multiplication, or division).
2. Perform the operation based on the user's input and print the result.
Example: If a user inputs 10, 5, and +, your program should display 10 + 5 = 15.

# Python Week 2 Assignment
1. Create an empty list called my_list.
2. Append the following elements to my_list: 10, 20, 30, 40.
3. Insert the value 15 at the second position in the list.
4. Extend my_list with another list: [50, 60, 70].
5. Remove the last element from my_list.
6. Sort my_list in ascending order.
7. Find and print the index of the value 30 in my_list.

# Python Week 3 Assignment
1. Create a function named calculate_discount(price, discount_percent) that calculates the final price after applying a discount. The function should take the original price (price) and the discount percentage (discount_percent) as parameters. If the discount is 20% or higher, apply the discount; otherwise, return the original price.
2. Using the calculate_discount function, prompt the user to enter the original price of an item and the discount percentage. Print the final price after applying the discount, or if no discount was applied, print the original price.

# Python Week 4 Assignment
1. ### File Read & Write Challenge 🖋️:
      Create a program that reads a file and writes a modified version to a new file.
2. ### Error Handling Lab 🧪:
      Ask the user for a filename and handle errors if it doesn’t exist or can’t be read.

# Python Week 5 Assignment
### Design Your Own Class! 🏗️
1. Create a class representing anything you like (a Smartphone, Book, or even a Superhero!).
2. Add attributes and methods to bring the class to life!
3. Use constructors to initialize each object with unique values.
4. Add an inheritance layer to explore polymorphism or encapsulation.
   
### Polymorphism Challenge! 🎭
Create a program that includes animals or vehicles with the same action (like move()). However, make each class define move() differently (for example, Car.move() prints "Driving" 🚗, while Plane.move() prints "Flying" ✈️).

# Python Week 7 Assignment
## Objective For this Assignment:
1. To load and analyze a dataset using the pandas library in Python.
2. To create simple plots and charts with the matplotlib library for visualizing the data.

## Submission Requirements
1. Submit a Jupyter notebook (.ipynb file) or Python script (.py file) containing:
2. Data loading and exploration steps.
3. Basic data analysis results.
4. Visualizations.
5. Any findings or observations.

### Task 1: Load and Explore the Dataset
1. Choose a dataset in CSV format (for example, you can use datasets like the Iris dataset, a sales dataset, or any dataset of your choice).
2. Load the dataset using pandas.
3. Display the first few rows of the dataset using .head() to inspect the data.
4. Explore the structure of the dataset by checking the data types and any missing values.
5. Clean the dataset by either filling or dropping any missing values.

### Task 2: Basic Data Analysis
1. Compute the basic statistics of the numerical columns (e.g., mean, median, standard deviation) using .describe().
2. Perform groupings on a categorical column (for example, species, region, or department) and compute the mean of a numerical column for each group.
3. Identify any patterns or interesting findings from your analysis.

### Task 3: Data Visualization
1. Create at least four different types of visualizations:
      Line chart showing trends over time (for example, a time-series of sales data).
      Bar chart showing the comparison of a numerical value across categories (e.g., average petal length per species).
      Histogram of a numerical column to understand its distribution.
      Scatter plot to visualize the relationship between two numerical columns (e.g., sepal length vs. petal length).
2. Customize your plots with titles, labels for axes, and legends where necessary.

## Web Development Week 1 Assignment
1. Create an index.html file.
2. Structure the document using DOCTYPE, html, head, and body.
   
### Note
Include at least:
1. A header with a title.
2. A nav with links.
3. A main section with some text content.
4. A footer with contact information. Ensure proper indentation and commenting.

### Tasks
1. Create a well-structured HTML5 document.
2. Use at least 5 different HTML elements.
3. Ensure semantic correctness.

## Web Development Week 2 Assignment
### Instructions
1. Create an index.html file.
2. Add an ordered list with roman numerals
3. Add an external image from pexels.com
4. Add a table of 5 contacts with; name, address, mobile and emails
5. Add a registration form
   
### Note
The registration form should have:
1. Name, email, password, and date fields.
2. A dropdown, radio buttons, and checkboxes.
3. Proper labels and placeholders.
4. Required fields and validation attributes.
5. Ensure proper indentation and commenting.

### Tasks
1. Create a well-structured HTML5 document.
2. Ensure semantic correctness.

## Web Development Week 3 Assignment
### Instructions
Create a style.css file. Apply CSS to a HTML page. Style elements using: Classes and IDs. Color and typography. Margins, paddings, and borders.

### Note
Include at least:
1. Use of 3 selectors
2. Style an image
3. Margin, Padding & Borders
4. Different font

### Tasks
1. Link an external CSS file.
2. Apply at least 3 different selectors.
3. Improve readability and aesthetics.

# Web Development Week 4 Assignment
### Instructions
1. Use Flexbox or CSS Grid.
2. Add a navigation bar and structure the content.
3. Use media queries to adjust layout for mobile, tablet, and desktop.

### Note
Include at least:
1. Navigation bar
2. Media queries

### Tasks
1. Apply Flexbox or Grid for layout.
2. Make the page responsive.
3. Test across different screen sizes.

# Web Development Week 5 Assignment
### Instructions
1. Create a script.js file and link it to a HTML.
2. Structure the document using DOCTYPE, html, head, and body.

### Note
Write JavaScript that:
      1. Changes text content dynamically.
      2. Modifies CSS styles via JavaScript.
      3. Adds or removes an element when a button is clicked.

### Tasks
1. Create a well-structured HTML5 document.
2. Use at least 5 different HTML elements.
3. Ensure semantic correctness.

# Database Week 1 Asignment
## 📚 Assignment Questions
1. Write an SQL query to create a new database called salesDB.
2. Write an SQL query to drop (delete) the database called demo.

# Database Week 2 Assignment
## 📚 Assignment Questions
1. Write an SQL query to retrieve the checkNumber, paymentDate, and amount from the payments table.
2. Write an SQL query to retrieve the orderDate, requiredDate, and status of orders that are currently 'In Process' from the orders table. Sort the results in descending order of orderDate
3. Write a query to display the firstName, lastName, and email of employees whose job title is 'Sales Rep' and order them in descending order of employeeNumber.
4. Write a query to retrieve all the columns and records from the offices table.
5. Write a query to fetch the productName and quantityInStock from the products table. Sort the results in ascending order of buyPrice and limit the output to 5 records.

# Database Week 3 Assignment
## 📚 Assignment Questions
### Question 1 🧑‍🎓
Write an SQL statement to create a table named student with the following columns:
1. id (an integer and the primary key)
2. fullName (a text field with a maximum of 100 characters)
3. age (an integer)
   
### Question 2 ➕
Write an SQL statement to insert at least 3 records into the student table.

### Question 3 🔄
Write an SQL statement to update the age of the student with ID 2 to 20 in the student table.

# Database Week 4 Assignment
## 📚 Assignment Questions
### Question 1
1. Write an SQL query to show the total payment amount for each payment date from payments table.
2. Display the payment date and the total amount paid on that date.
3. Sort the results by payment date in descending order.
4. Show only the top 5 latest payment dates.

### Question 2
1. Write an SQL query to find the average credit limit of each customer from customers table.
2. Display the customer name, country, and the average credit limit.
3. Group the results by customer name and country.

### Question 3
1. Write an SQL query to find the total price of products ordered from orderdetails table.
2. Display the product code, quantity ordered, and the total price for each product.
3. Group the results by product code and quantity ordered.

### Question 4
1. Write an SQL query to find the highest payment amount for each check number from payments table.
2. Display the check number and the highest amount paid for that check number.
3. Group the results by check number.

# Database Week 5 Assignment
## 📚 Assignment Questions
### Question 1 🗑️
Write an SQL query to drop an index named IdxPhone from customers table.

### Question 2 👤
Write an SQL query to create a user named bob with the password 'S$cu3r3!' , restricted to the localhost hostname.

### Question 3 🔑
Write an SQL query to grant the INSERT privilege to the user bob on the salesDB database.

### Question 4 🔐
Write an SQL query to change the password for the user bob to 'P$55!23'

# Database Week 6 Assignment
## 📚 Assignment Questions
### **Question 1 🧑‍💼**  
**Write an SQL query** to get the **firstName**, **lastName**, **email**, and **officeCode** of all employees.  
Use an **INNER JOIN** to combine the **employees** table with the **offices** table using the **officeCode** column.

### **Question 2 🛍️**  
**Write an SQL query** to get the **productName**, **productVendor**, and **productLine** from the **products** table.  
Use a **LEFT JOIN** to combine the **products** table with the **productlines** table using the **productLine** column.

### **Question 3 📦**  
**Write an SQL query** to retrieve the **orderDate**, **shippedDate**, **status**, and **customerNumber** for the first 10 orders.  
Use a **RIGHT JOIN** to combine the **customers** table with the **orders** table using the **customerNumber** column.

# Database Week 7 Assignment 
## 📚 Assignment Questions
### Question 1 Achieving 1NF (First Normal Form) 🛠️
Task:
- You are given the following table **ProductDetail**:

| OrderID | CustomerName  | Products                        |
|---------|---------------|---------------------------------|
| 101     | John Doe      | Laptop, Mouse                   |
| 102     | Jane Smith    | Tablet, Keyboard, Mouse         |
| 103     | Emily Clark   | Phone                           |


- In the table above, the **Products column** contains multiple values, which violates **1NF**.
- **Write an SQL query** to transform this table into **1NF**, ensuring that each row represents a single product for an order

### Question 2 Achieving 2NF (Second Normal Form) 🧩
- You are given the following table **OrderDetails**, which is already in **1NF** but still contains partial dependencies:

| OrderID | CustomerName  | Product      | Quantity |
|---------|---------------|--------------|----------|
| 101     | John Doe      | Laptop       | 2        |
| 101     | John Doe      | Mouse        | 1        |
| 102     | Jane Smith    | Tablet       | 3        |
| 102     | Jane Smith    | Keyboard     | 1        |
| 102     | Jane Smith    | Mouse        | 2        |
| 103     | Emily Clark   | Phone        | 1        |

- In the table above, the **CustomerName** column depends on **OrderID** (a partial dependency), which violates **2NF**. 

- Write an SQL query to transform this table into **2NF** by removing partial dependencies. Ensure that each non-key column fully depends on the entire primary key.
