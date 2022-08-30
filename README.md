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
![Screenshot (143)](https://user-images.githubusercontent.com/62988235/187326332-97e0850a-3f56-45a5-a79a-c1093a9bc4a5.png)

#About 
![Screenshot (144)](https://user-images.githubusercontent.com/62988235/187326366-916cbaf7-81cf-42f0-b397-1e80a10b9355.png)

#Contact
![Screenshot (145)](https://user-images.githubusercontent.com/62988235/187326404-954c7038-73b4-43de-8366-903b2400b8c4.png)

#Login
![Screenshot (147)](https://user-images.githubusercontent.com/62988235/187326443-39ad234c-3a34-42c6-8985-e2732dd41a29.png)

#Register
![Screenshot (148)](https://user-images.githubusercontent.com/62988235/187326519-40250297-0d0b-4b19-af9e-242339bd1994.png)

#Loggedin
![Screenshot (149)](https://user-images.githubusercontent.com/62988235/187326571-76eea516-36e8-46b2-8a5d-eadad83eff5c.png)

Deployment 
![Screenshot (151)](https://user-images.githubusercontent.com/62988235/187326626-b402717d-8340-4f29-b552-7caf502c9d6d.png)


## live deploment
1. <a href="https://github.com/nikhilspy/tree" target="_blank">Github</a>
2. <a href="https://nikhil-xenon.herokuapp.com/" target="_blank">Heroku</a>


## For Sponsor or Projects Enquiry
1. Email - nikhilchemistry282@gmail.com
2. LinkedIn - [Nikhil Srivastava](https://www.linkedin.com/in/nikhil-srivastava-9b372a1a1/ "Nikhil Srivastava on LinkedIn")
3. Portfolio - [Nikhil  Srivastava](https://nikhilspy.github.io/Portfolio/)

