# Project DataBase

**Description:**

The Project DataBase is a relational database designed to manage information related to students in College town, departments, locations, rooms, and parents. It is intended to be a comprehensive solution for educational institutions or organizations that require a robust system for storing and organizing data about students, their academic performance, departmental information, geographical locations, living arrangements, and parental details.

## Database Schema

1. **Students Table:**
   - Stores information about students, including their unique identifier, names, gender, faculty, grade, contact details, and hire date.

2. **Departments Table:**
   - Manages details about different departments, such as department ID, name, and the ID of the department manager.

3. **Locations Table:**
   - Tracks information about locations, including a unique identifier, governrate name, governrate index, and a foreign key linking to the Students table.

4. **Room Table:**
   - Contains data about rooms, such as room ID, building ID, capacity, services provided, and a foreign key linking to the Students table.

5. **Parent Table:**
   - Stores details about parents, including a unique identifier, names, email, phone number, and a foreign key linking to the Students table.

## Data Population

The database includes sample data to illustrate its functionality. It showcases students enrolled in various faculties, assigned to departments, living in different locations and rooms, and having parents associated with them.

## Example Queries

- Retrieve a list of students along with their respective departments.
- Identify the parents of a specific student.
- Find the location and room details for a given student.
- Obtain information about the departmental manager.

## Usage

This database can be utilized as a foundation for building applications related to student management systems, academic institutions, or any scenario requiring the organized storage of student, department, location, room, and parent data.


## Final.txt
-this file include tables and data to insert data in tables

