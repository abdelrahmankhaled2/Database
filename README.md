
# Project DataBase

## Description

This project is a database management system for handling student information in an College town. It offers basic CRUD operations, navigation, and reporting functionalities. The database includes tables for students, departments, locations, rooms, and parents, with relationships and constraints.

### Features

1. **Navigation Block**
   - Facilitates easy navigation between different sections of the application.

2. **Database Triggers**
   - Implements at least one database trigger for automated actions on insert, update, or delete events.

3. **Application Triggers**
   - Incorporates application triggers as needed for specific event handling.

4. **Select Operation for Each Table**
   - Provides select operations for each table to retrieve data.

5. **Insert Operation for Each Table**
   - Supports insert operations for adding new records.

6. **Update Operation for Each Table**
   - Implements update operations to modify existing records.

7. **Delete Operation for Each Table**
   - Enables delete operations to remove records.

8. **Record Navigation**
   - Creates forms with buttons for easy record navigation.

9. **Master Details Form**
   - Displays detailed information about a selected record, potentially including related records.

10. **Static List Items**
    - Includes static list items for predefined options in certain fields.

11. **Static Report**
    - Provides at least one static report for specific information.

12. **Calling Reports from Forms**
    - Allows direct report calls from forms for enhanced reporting.

### Tables

1. **Students Table**
   - Attributes: student_id, first_name, last_name, gender, faculty_name, grade, phone_number, email, hire_date

2. **Departments Table**
   - Attributes: department_id, department_name, manager_id

3. **Locations Table**
   - Attributes: id, governrate_name, governrate_index, student_id

4. **Room Table**
   - Attributes: room_id, building_id, capacity, serves, student_id

5. **Parent Table**
   - Attributes: parent_id, first_name, last_name, email, phone_number, student_id

## Example Queries

- Retrieve a list of students along with their respective departments.
- Identify the parents of a specific student.
- Find the location and room details for a given student.
- Obtain information about the departmental manager.


## Final.txt
-this file include tables and data to insert data in tables

