# College-Admin-Software
A college management system built using the Django framework. It is designed for interactions between students and teachers. Features include attendance, marks and timetable.

#Team member
1-Varun Pratap Singh
2-Arjun Saxena
3-Aman Pratap Singh


## Installation

Python and Django need to be installed

```bash
1. pip install django
2. pip install -r requirements.txt
```

## Usage

Go to the CollegeAdmin folder and run

```bash
python manage.py runserver
```

Then go to the browser and enter the URL **http://127.0.0.1:8000/**


## Login

The login page is common for students and teachers.  
The username is their name and the password for everyone is 'project123'.  

Example usernames:  
student- 'Samarth'  
teacher- 'trisilane'  

You can access the Django admin page at **http://127.0.0.1:8000/admin** and login with the username 'admin' and the above password.

Also, a new admin user can be created using

```bash
python manage.py createsuperuser
```

## Users

New students and teachers can be added through the admin page. A new user needs to be created for each. 

The admin page is used to modify all tables such as Students, Teachers, Departments, Courses, Classes etc.

**For more details regarding the system and features please refer to the reports included.**

## Update 

Added method to reset attendance time range in Django Admin page.

This is present in Django Admin -> Attendance (http://127.0.0.1:8000/admin/info/attendanceclass/).  
Start Date: Start Date of Attendance period  
End Date: End Date of Attendance period

This will delete all present attendance data and create new attendance objects for the given time range. 
