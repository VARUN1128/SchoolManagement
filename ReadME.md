# EduManage

## Introduction
Welcome to EduManage, a comprehensive school management system designed to streamline the administrative and academic functions of educational institutions. EduManage provides a robust platform for managing student information, courses, faculty, and various other aspects of school operations.


## How to Install and Run this project?

### Pre-Requisites:
1. Install Git Version Control
[ https://git-scm.com/ ]

2. Install Python Latest Version
[ https://www.python.org/downloads/ ]

3. Install Pip (Package Manager)
[ https://pip.pypa.io/en/stable/installing/ ]

*Alternative to Pip is Homebrew*

### Installation
**1. Create a Folder where you want to save the project**

**2. Create a Virtual Environment and Activate**

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
$  ./venv/scripts/activate
```

For Mac
```
$  source venv/bin/activate
```

**3. Clone this project**
```
$  git clone https://github.com/venkideshVenu/ST-Lab.git
```

Then, Enter the project
```
$  cd django-student-management-system
```

**4. Install Requirements from 'requirements.txt'**
```python
$  pip install -r requirements.txt
```

**5. Run Database Migrations**

```
python manage.py makemigrations
```
**6. Run Migrations**

```
python manage.py migrate
```

**7. Now Run Server**

Command for PC:
```python
$ python manage.py runserver
```

Command for Mac:
```python
$ python3 manage.py runserver
```

## Technology Used
* Frontend : HTML, CSS, Javascript
* Backend : Python Django
* Database : SQL Lite
