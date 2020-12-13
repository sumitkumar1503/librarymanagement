# Library Management
![developer](https://img.shields.io/badge/Developed%20By%20%3A-Sumit%20Kumar-red)
---
## screenshots
### Homepage
![homepage snap](https://github.com/sumitkumar1503/librarymanagement/blob/master/static/screenshots/homepage.png?raw=true)
### Admin Dashboard
![dashboard snap](https://github.com/sumitkumar1503/librarymanagement/blob/master/static/screenshots/adminhomepage.png?raw=true)
### Available Book
![invoice snap](https://github.com/sumitkumar1503/librarymanagement/blob/master/static/screenshots/availablebook.png?raw=true)
### Issue Book
![doctor snap](https://github.com/sumitkumar1503/librarymanagement/blob/master/static/screenshots/issuebook.png?raw=true)
### Issued Book
![doctor snap](https://github.com/sumitkumar1503/librarymanagement/blob/master/static/screenshots/bookissued.png?raw=true)
---
## Functions
### Admin
- Create Admin account and Login.
- Can Add, View, Book
- Can Issue Book (added by Admin) to registered student.
- Can view Issued book with issued date and expiry date.
- Can view Fine (10 rupees for each day after expiry date).
- Can View Students that are registered into system.

### Student
- Create account and Login.
- Can view their issued book only with expiry date and fine(if there any otherwise 0)
---

## HOW TO RUN THIS PROJECT
- Install Python(3.7.6) (Dont Forget to Tick Add to Path while installing Python)
- Open Terminal and Execute Following Commands :
```
python -m pip install -r requirements. txt
```
- Download This Project Zip Folder and Extract it
- Move to project folder in Terminal. Then run following Commands :
```
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
```
- Now enter following URL in Your Browser Installed On Your Pc
```
http://127.0.0.1:8000/
```

## CHANGES REQUIRED FOR CONTACT US PAGE
- In settins.py file, You have to give your email and password
```
EMAIL_HOST_USER = 'youremail@gmail.com'
EMAIL_HOST_PASSWORD = 'your email password'
EMAIL_RECEIVING_USER = 'youremail@gmail.com'
```

## Drawbacks/LoopHoles
- Anyone can be Admin.

## Feedback
Any suggestion and feedback is welcome. You can message me on facebook
- [Contact on Facebook](https://fb.com/sumit.luv)
- [Subscribe my Channel LazyCoder On Youtube](https://youtube.com/lazycoders)
