# ReadMe for Library Automation Project

## Project Overview

The Library Automation Project is designed to streamline library management processes, including book inventory, student information, and book borrowing/returning. Below is an explanation of how to use each section of the application and what functionalities they provide.

---

## Contents

1. **Files Included**:

   - `library project SQLQuery.sql`: Full SQL script containing table creation, Stored Procedures, Triggers, Views, and Functions.
   - `ER Diagram`: A folder containing the ER Diagram file.
   - `Rules.sql`: A script outlining project rules and validation steps.
   - `Abdelrahman_mohamed_200709050`: A folder containing additional resources.
   - **Video Link**: [Provide video link here].

2. **Key Features**:

   - **Stored Procedures (SPs)**:
     - Adding, updating, and deleting records for books and members.
     - Viewing available books.
   - **Triggers**:
     - Validating positive quantities of books.
     - Updating book status upon borrowing.
     - Preventing member deletion if they have active borrowings.
   - **View**:
     - `BorrowedBooksView`: Displays borrowed book details along with member information.
   - **Functions**:
     - Calculating total books.
     - Counting active members.
     - Calculating penalties for members.

---

## Application Walkthrough

### 1. **Login Page**
   - **Purpose**: Allows authorized users to access the system.
   - **Features**:
     - Enter a **Username** and **Password** to log in.
     - Click the **Login** button to proceed to the Dashboard.
     - Social media icons are placeholders and non-functional.

---

### 2. **Dashboard**
   - **Purpose**: Acts as the central navigation hub for the system.
   - **Features**:
     - Buttons for managing books, students, issuing/returning books, and viewing records.
     - Exit button to close the application.

---

### 3. **Add Book Page**
   - **Purpose**: Allows users to add new books to the library inventory.
   - **Fields**:
     - **Book Name**
     - **Book Author Name**
     - **Book Publication**
     - **Book Purchase Date**
     - **Book Price**
     - **Book Quantity**
   - **Actions**:
     - **Save**: Adds the entered book details to the database.
     - **Cancel**: Clears the form without saving.

---

### 4. **View Books Page**
   - **Purpose**: Displays all books in the inventory and allows updates or deletions.
   - **Features**:
     - Search for a book by name.
     - Update a book's price or quantity.
     - Delete a book from the inventory.
   - **Actions**:
     - Enter the book name and click **Search** to find a book.
     - Modify fields and click **Update** to save changes.
     - Click **Delete** to remove a book from the database.

---

### 5. **Add Student Page**
   - **Purpose**: Allows users to add new students to the library system.
   - **Fields**:
     - **Student Name**
     - **Student Number**
     - **Department**
     - **Education Level**
     - **Student Contact**
   - **Actions**:
     - **Save**: Adds the student details to the database.
     - **Cancel**: Clears the form without saving.

---

### 6. **View Students Page**
   - **Purpose**: Displays student information and allows updates or deletions.
   - **Features**:
     - Search for students by name or student number.
     - Update a student’s education level or contact details.
     - Delete a student record.
   - **Actions**:
     - Enter a search term and click **Search**.
     - Update fields and click **Update** to save changes.
     - Click **Delete** to remove a student record.

---

### 7. **Issue Books Page**
   - **Purpose**: Issues books to students.
   - **Fields**:
     - **Student Name**
     - **Department**
     - **Education Level**
     - **Student Contact**
     - **Book Name**
     - **Book Issue Date**
   - **Actions**:
     - Enter the student number and click **Search** to populate student details.
     - Select a book and issue date, then click **Issue Book**.
     - The system restricts issuing more than three books per student.

---

### 8. **Return Books Page**
   - **Purpose**: Manages book returns and tracks returned and issued books.
   - **Features**:
     - Displays all currently issued books in the top section.
     - Displays returned books in the bottom section.
   - **Actions**:
     - Mark books as returned to update the database.

---

## Submission Guidelines

1. **What to Include**:
   - Ensure all files and database scripts are included in the final submission package.
   - Verify that all Stored Procedures, Triggers, Views, and Functions work as expected.
   - Record a demonstration video showcasing:
     - How to log in.
     - How to add books and students.
     - Issuing and returning books.
     - Viewing and managing records.

2. **Video Link**:
   - Add the video link here: [Insert Link].

---

## Contact Information

- **Student Name**: Abdelrahman Mohamed  
- **Student Number**: 200709050  
- **Email**: [abdelrahman.mohamed20@ogr.atauni.edu.tr](mailto:abdelrahman.mohamed20@ogr.atauni.edu.tr)

