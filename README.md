![Screenshot (245)](https://github.com/user-attachments/assets/a68c9c9a-2b8f-4cb6-9346-1a5a909cd083)# College Management System

## Overview
This is a **Java Swing-based College Management System** that allows users to manage student data, including adding, searching, and deleting student records. The system uses **MySQL** as the database and provides a user-friendly interface built with Java Swing.

## Features
- **User Authentication** 
- **Add Student Records**
- **Search Student Records**
- **Delete Student Records**
- **Graphical User Interface (GUI) using Java Swing**
- **MySQL Database Integration**

## Technologies Used
- **Java (Swing, AWT)** - GUI development
- **MySQL** - Database for storing student records
- **JDBC** - Connecting Java to MySQL
- **Apache NetBeans IDE** - Development Environment
- **Git & GitHub** - Version control

## Setup Instructions
### Prerequisites
- Install **JDK 21** (or compatible version)
- Install **NetBeans IDE**
- Install **MySQL Server & MySQL Workbench**

### Database Setup
1. Open **MySQL Workbench** and create a new database:
   ```sql
   CREATE DATABASE college;
   USE college;
   ```
2. Create the `student` table:
   ```sql
   CREATE TABLE student (
       rollNumber VARCHAR(10) PRIMARY KEY,
       studentName VARCHAR(50),
       class VARCHAR(50)
   );
   ```
3. Insert some sample data:
   ```sql
   INSERT INTO student VALUES ('12345', 'Lisa', 'Music');
   INSERT INTO student VALUES ('12343', 'Virat', 'Cricket');
   INSERT INTO student VALUES ('123', 'Apple', 'Mobile');
   ```

### Running the Project
1. **Clone the repository**:
   ```bash
   git clone https://github.com/dhanish03/College_Management_System.git
   ```
2. **Open the project in NetBeans**
3. **Configure Database Connection** in the project:
   - Update the `DatabaseConnection.java` file with your **MySQL credentials**.
4. **Run the Application** in NetBeans.

## Screenshots
![Screenshot (239)](https://github.com/user-attachments/assets/436ef58c-1ca0-4734-a605-364e13843bd0)
![Screenshot (240)](https://github.com/user-attachments/assets/eb41df19-05dd-4384-a7f5-e69a20612511)
![Screenshot (241)](https://github.com/user-attachments/assets/78154296-cb73-45aa-a07c-a74df01e193c)
![Screenshot (242)](https://github.com/user-attachments/assets/95adabd0-3152-485a-bee2-d427d4405cc6)
![Screenshot (243)](https://github.com/user-attachments/assets/471704c9-24eb-4a4c-b1d8-599c9e3fd88a)
![Screenshot (244)](https://github.com/user-attachments/assets/d98ff483-7af3-423a-adfa-96eb720128e3)
![Screenshot (245)](https://github.com/user-attachments/assets/ac0dbff8-192c-4862-9b4e-1f8a38574049)









## Contributing
Feel free to submit pull requests if you want to improve the project.

## License
This project is open-source under the **MIT License**.

