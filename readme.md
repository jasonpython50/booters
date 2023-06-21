# Blog Website
This is a blog website built with Flask, a micro web framework written in Python. This is for newbies wanting to try the flask python micro-framework.

## Features

1. User Registration
2. User Login & Logout
3. User account management
4. Blog Post Creation
5. Blog Post Interaction (Reading, Commenting)
6. Password Reset.

## Setup and run the application
1. Clone the repository.
2. Create a virtual environment and install dependencies using pipenv.
3. Alternatively you can use the requirements.txt file. in that case:
```python
pip install -r requirements.txt
```
4. set environment variables:
```python
set FLASK_APP=blog.py
```
5. initialize database:
```python
flask db init
flask db migrate -m "optional message"
flask db upgrade
```
6. run the project:
```python
flask run
```
7. The application will start running on http://127.0.0.1:5000

### issues
Feel free to report any issues.