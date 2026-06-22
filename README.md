# 📚 Student Database Android Application

## 📌 Project Overview

Student Database is a simple Android application developed using Kotlin.  
This application allows users to manage student records using SQLite Database.

The main purpose of this project is to perform basic CRUD operations:
- Create (Insert Student Data)
- Read (View Student Records)
- Update Existing Data
- Delete Student Records

The application contains multiple activities, custom UI components, SQLite database connectivity, and custom AlertDialog implementation.


---

# 🛠 Technology Used

- Programming Language: Kotlin
- IDE: Android Studio
- Database: SQLite
- UI Design: XML
- Platform: Android


---

# 📱 Application Features

## 1. Main Activity

The application starts from MainActivity.

Features:
- Attractive home screen
- Background image added using drawable resources
- Button navigation system

A button is created on the first page.

When the user clicks the button, Intent is used to move from MainActivity to the Student Database page.

Concept Used:

- Explicit Intent
- Button Click Listener


---

# 2. Student Database Page

The second activity contains the main student management system.

User can enter:

- Student Name
- Student Email
- Student UID


Operations available:

➕ Add Student  
📖 View Data  
✏ Update Data  
🗑 Delete Data  


---

# 🗄 SQLite Database

SQLite database is implemented using DBHelper class.

DBHelper extends SQLiteOpenHelper class.

Database Name:

StudentDB


Table Name:

Student


Columns:

UID
Name
Email


Functions Created:

## Insert Data

Used to store student information into SQLite database.


## View Data

Used to fetch all records from SQLite database.


## Update Data

Used to modify existing student details using UID.


## Delete Data

Used to remove student records from database.


---

# 🎨 User Interface Design

The UI is created using XML layouts.

Custom designs added:

- Rounded EditText design
- Rounded Button design
- Better spacing and padding
- Modern looking student form


Drawable XML files:

button_design.xml

Used for customized buttons.


edittext_design.xml

Used for attractive input fields.


dialog_bg.xml

Used for custom AlertDialog background.


---

# 💬 Custom AlertDialog

Instead of default AlertDialog, a custom dialog layout is created.

File:

dialog_student_records.xml


Features:

- Custom title
- Better record display
- ScrollView support
- Custom close button
- Rounded card design


Implementation:

LayoutInflater is used to attach custom XML layout with AlertDialog.


---

# 📂 Project Files


## MainActivity.kt

Handles:
- First screen
- Button click
- Navigation using Intent


## activity_main.xml

Contains:
- Home UI
- Background image
- Navigation button


## PageActivity2.kt

Handles:

- Add Student
- View Student Records
- Update Data
- Delete Data
- Custom AlertDialog


## activity_page2.xml

Contains:

- Student Database UI
- EditText fields
- Operation buttons


## DBHelper.kt

Handles:

- Database creation
- Table creation
- SQLite CRUD operations


---

# ⚙ Working Flow

1. User opens application

2. MainActivity is displayed

3. User clicks Notebook button

4. Intent opens Student Database page

5. User enters student details

6. Data is stored inside SQLite Database

7. Records can be viewed, updated, and deleted


---

# 📚 Concepts Implemented

✔ Activity Lifecycle  
✔ Intent  
✔ Kotlin Programming  
✔ XML UI Designing  
✔ SQLite Database  
✔ CRUD Operations  
✔ Custom Drawable Design  
✔ Custom AlertDialog  
✔ LayoutInflater  


---

# Developer

Developed by:

Aryan Raj

Android App Development Training Project
