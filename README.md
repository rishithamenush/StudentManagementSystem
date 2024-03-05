# Python base Student Management System

### A. Admin Users Can

1. See Overall Summary Charts of Stuudents Performance, Staffs Perfomrances, Courses, Subjects, Leave, etc.
2. Manage Staffs (Add, Update and Delete)
3. Manage Students (Add, Update and Delete)
4. Manage Course (Add, Update and Delete)
5. Manage Subjects (Add, Update and Delete)
6. Manage Sessions (Add, Update and Delete)
7. View Student Attendance
8. Review and Reply Student/Staff Feedback
9. Review (Approve/Reject) Student/Staff Leave

### B. Staff/Teachers Can

1. See the Overall Summary Charts related to their students, their subjects, leave status, etc.
2. Take/Update Students Attendance
3. Add/Update Result
4. Apply for Leave
5. Send Feedback to HOD

### C. Students Can

1. See the Overall Summary Charts related to their attendance, their subjects, leave status, etc.
2. View Attendance
3. View Result
4. Apply for Leave
5. Send Feedback to HOD

### Installation

**1. Create a Virtual Environment and Activate**

Install Virtual Environment First

```
$  pip install virtualenv
```

Create Virtual Environment

For Windows

```
$  python -m venv venv
```

For Mac

```
$  python3 -m venv venv
```

Activate Virtual Environment

For Windows

```
$  source venv/scripts/activate
```

For Mac

```
$  source venv/bin/activate
```

Then, Enter the project

```
$  cd django-student-management-system
```

**2. Install Requirements from 'requirements.txt'**

```python
$  pip install -r requirements.txt
```

**3. Add the hosts**

- Got to settings.py file
- Then, On allowed hosts, Add [‘*’].

```python
ALLOWED_HOSTS = ['*']
```

_No need to change on Mac._

**4. Now Run Server**

Command for PC:

```python
$ python manage.py runserver
```

Command for Mac:

```python
$ python3 manage.py runserver
```

**5. Login Credentials**

Create Super User (HOD)

```
$  python manage.py createsuperuser
```

Then Add Email, Username and Password

**or Use Default Credentials**

_For HOD /SuperAdmin_
Email: roAdmin@gmail.com
Password: roAdmin

_For Staff_
Email: roStaff@gmail.com
Password: roStaff

_For Student_
Email: roStudent@gmail.com
Password: roStudent
