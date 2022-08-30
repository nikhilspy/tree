# tree


## Features of this Project
1. Login
2. Contact US  Form 
3. Register

## Technologies Uesd
1. HTML
2. CSS
3. Javascript
4. Django

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
$  source venv/scripts/activate
```

For Mac
```
$  source venv/bin/activate
```

**3. Clone this project**
```
$  git clone
```

Then, Enter the project
```
$  cd django-student-management-system
```

**4. Install Requirements from 'requirements.txt'**
```python
$  pip install -r requirements.txt
```

**5. Add the hosts**

- Got to settings.py file 
- Then, On allowed hosts, Add [‘*’]. 
```python
ALLOWED_HOSTS = ['*']
```
*No need to change on Mac.*


**6. Now Run Server**

Command for PC:
```python
$ python manage.py runserver
```

Command for Mac:
```python
$ python3 manage.py runserver
```

**7. Login Credentials**

Create Super User (HOD)
```
$  python manage.py createsuperuser
```
## setting up of Database Local

1. Install Xampp
2. Create a database named *xenon*
3. Run the command *python manage.py makemigration*
4. Run the command *python manage.py migrate*
5. Run the command *python manage.py runserver*

DATABASES = {
     'default': {
         'ENGINE'  : 'django.db.backends.mysql',
         'NAME'    : 'xenon', 
         'USER'    : 'root', 
         'PASSWORD': '',
         'HOST'    : 'localhost',
         'PORT'    : '3306',
     }


## Screen Shot 
#Home 
![plot](./screenshot/Sc![Screenshot (143)](https://user-images.githubusercontent.com/62988235/187326069-24f6c670-0231-4bec-8ad0-3f22eb341eef.png)
reenshot (143).png)

#About

#Contact




## live deploment
1. <a href="https://github.com/nikhilspy/tree" target="_blank">Github</a>
2. <a href="https://nikhil-xenon.herokuapp.com/" target="_blank">Heroku</a>


## For Sponsor or Projects Enquiry
1. Email - nikhilchemistry282@gmail.com
2. LinkedIn - [Nikhil Srivastava](https://www.linkedin.com/in/nikhil-srivastava-9b372a1a1/ "Nikhil Srivastava on LinkedIn")
3. Portfolio - [Nikhil  Srivastava](https://nikhilspy.github.io/Portfolio/)

