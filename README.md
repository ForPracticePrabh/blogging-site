# Blogging Site using FLASK
Flask is a Python Framework used to make web applications.
We have used Flask Framework to create a blogging website.

>Features
- User Authorisation: Registering a User using Flask-Login Package
- Database connectivity using SQLAlchemy
- Password hashing using Werkzeug
- Authorised user can only Create, Update and Delete his Blogs
- Other Users can only view other blogs but cannot edit it.
- Home page displays all the Blogs, their authors and the content.

![alt txt](https://github.com/pradnyalgandhi/Blogging-Site/blob/master/myproject/static/profile_pics/Picture1.png "Blogging Site")

## Installation

1. Install Python and Anaconda in your Computer.

[Python](https://www.python.org/downloads/)
[Anaconda](https://www.anaconda.com/distribution/)

2. Open your command prompt and Create a Virtual Environment
```bash
conda create --name myenv
```
![alt txt](https://github.com/pradnyalgandhi/Blogging-Site/blob/master/myproject/static/profile_pics/Picture2.png)

3. Activate your virtual Environment
```bash
activate my env
```
4. Install the requirements.txt file
```bash
pip install -r requirements.txt
```

5. After cloning the repository delete the __pycache__ and __migrations__ folder

6. Initiate the database using the following commands
```bash
flask db init
flask db migrate -m
flask db upgrade
```

7. cd to your app.py file and run it in the Command Prompt using the following command
```bash
python app.py
```
## Licence
[MIT](https://choosealicense.com/licenses/mit/)
