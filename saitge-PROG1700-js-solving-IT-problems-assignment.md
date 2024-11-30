### **Assignment: Applying Logic Principles to Solve Problems in IT**

**Course:** PROG1700 - Logic and Programming  
**Weight:** 25% of Final Grade  
**Due Date:** See Brightspace  

---

### **Assignment Overview**
In this assignment, you will solve real-world IT problems using **procedural JavaScript**. Each problem focuses on handling user input, processing data, and displaying results in a web application. You will implement and test the provided scenarios, integrating HTML and JavaScript to create functional programs.

This assignment will assess your ability to use JavaScript to solve technical problems in IT.
- This is not a **group project**
- No **code sharing**
- Work through solving the problem.  **Avoid** copying `code`.

---

### **Assignment Requirements**
You are tasked with completing **four programs** from the list below.

### **Submission Instructions**
1. Create separate HTML and JavaScript files for each program. Name the files as follows:
- **wxxxxxxx_email_parser.html**
- **wxxxxxxx_email_parser.js**
- **wxxxxxxx_decimal_converter.html**
- **wxxxxxxx_decimal_converter.js**
- **wxxxxxxx_export_CSV.html**
- **wxxxxxxx_export_CSV.js**
- **wxxxxxxx_search_query.html**
- **wxxxxxxx_search_query.js**

---

2. Ensure your programs meet the functionality requirements and are appropriately styled for clarity. (Use comments to describe your code.)

3. Zip all your files in one archive using your student ID **wxxxxxxx.zip or wxxxxxxx.7z** submit them via **Brightspace** by **the deadline**.

---

#### **Program 1: Parsing and Displaying Names from Email Addresses**
- Create a program that takes an array of email addresses in the format `first_name.last_name@domain.ca`.
- Parse each email to extract and display the first name and last name in a human-readable format (e.g., **John Doe**).  
- Display the results as a list of names on the HTML page.
- Be sure to **capitalise** the **F**irst **L**etter for both the first name and last name.

```javascript
const emails = [
    "john.doe@domain.ca",
    "jane.smith@domain.ca",
    "alice.jones@domain.ca",
    "bob.miller@domain.ca"
];
```
**Program Output**
```
John Doe
Jane Smith
Alice Jones
Bob Miller
```
---

#### **Program 2: Decimal to Binary and Hex Converter**
- Create a converter tool that prompts the user to enter a decimal number and select a conversion option: binary or hexadecimal.  
- Validate user input to ensure it is a valid decimal number.  
- Allow the user to repeat conversions until they type "exit."  
- Display results dynamically in the HTML document.

---

#### **Program 3: Exporting an Array to CSV format**
- Use the array below and export the array to CSV format
- The CSV format should have the table columns for the first row. (e.g., `f_name, l_name, email`)
- Display the generated CSV content in the browser using a `<pre>` tag in the HTML document for proper formatting.

```javascript
const users = [
    ["John", "Doe", "john.doe@domain.ca"],
    ["Jane", "Smith", "jane.smith@domain.ca"],
    ["Alice", "Jones", "alice.jones@domain.ca"],
    ["Bob", "Miller", "bob.miller@domain.ca"]
];
```
**Program Output**
```
   f_name,l_name,email
   John,Doe,john.doe@domain.ca
   Jane,Smith,jane.smith@domain.ca
   Alice,Jones,alice.jones@domain.ca
   Bob,Miller,bob.miller@domain.ca
```
---

#### **Program 4: Search Function Using an Array**
- Create a search tool that prompts the user for a search term.  
- Search an array of email addresses to find matches (case-insensitive).  
- Display matching results dynamically on the page, or display "No results found" if no match exists.

```javascript
const emails = [
    "john.doe@domain.ca",
    "jane.smith@domain.ca",
    "alice.jones@domain.ca",
    "bob.miller@domain.ca"
];
```
---

### **Grading Rubric (100%)**

| **Criteria**                 | **Weight** | **Exemplary (90-100%)**                                                                                  | **Proficient (75-89%)**                                                   | **Developing (60-74%)**                                                 | **Needs Improvement (<60%)**                                           |
|------------------------------|------------|----------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------|---------------------------------------------------------------------------|-------------------------------------------------------------------------|
| **Functionality**            | 40%        | Program works perfectly as described, with no bugs or errors.                                            | Program works with minor issues that do not affect core functionality.    | Program has functionality issues that partially meet requirements.      | Program does not function or fails to meet basic requirements.          |
| **Input Validation**         | 20%        | Input is thoroughly validated with clear error handling.                                                 | Input validation is implemented but has minor gaps.                       | Input validation is minimal or occasionally fails.                      | No input validation or ineffective handling of invalid input.           |
| **Dynamic Output Display**   | 20%        | Output is correctly and dynamically displayed on the web page as specified.                              | Output is displayed but with minor formatting issues or inconsistencies.  | Output is occasionally inaccurate or poorly formatted.                  | Output is incorrect or not dynamically displayed on the web page.       |
| **Code Quality and Comments**| 10%        | Code is well-organized, readable, and includes clear comments explaining the logic.                       | Code is readable, with some comments explaining the logic.                | Code is poorly organized or lacks sufficient comments.                  | Code is disorganized and lacks comments.                                |
| **Creativity and Effort**    | 10%        | Extra effort is evident in the program, such as additional features or enhanced design elements.          | Program meets requirements without extra features.                        | Program meets most requirements but lacks effort in design or logic.    | Program is incomplete or lacks sufficient effort.                       |

---

### **Tips for Success**
1. **Test Your Programs Thoroughly:** Ensure your programs handle edge cases, such as invalid inputs or empty arrays.
2. **Use Procedural JavaScript:** Avoid advanced JavaScript concepts like classes or external libraries to focus on procedural programming.
3. **Follow Best Practices:** Comment your code, use meaningful variable names, and maintain consistent formatting.
4. **Reach Out for Help:** If you encounter difficulties, don't hesitate to ask questions during class or office hours.

---

