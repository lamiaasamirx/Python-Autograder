# Python Auto-grader Web Application


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Library Dependencies:

Since we need certain libraries in order to make it work as you might not have all the necessary libraries.
Here’s the list,
```

flask
flask_login
flask_wtf
flask_sqlalchemy
flask_bcrypt
flask_login
flask_mail
wtforms
wtforms.validators
itsdangerous
os
werkzeug.utils
datetime
```

## Installing

A step by step series of examples that tell you how to get a development env running

###**1. Installing Flask and the Necessary, Associated Libraries:**
```
flask
flask_login
flask_wtf
flask_sqlalchemy
flask_bcrypt
flask_login
flask_mail
```
![img.PNG](Capture.PNG)

###**2. Importing other Necessary Libraries:**
```
wtforms
wtforms.validators
itsdangerous
os
werkzeug.utils
datetime
```

   ![img.PNG](Capture1.PNG)

###**3. Run the app from the run.py file**

### 4. Output


**Registering a new account (student or instructor):**

![img_3.png](PHOTO-2021-02-04-20-27-55.jpg)

**Log in**

![img_3.png](PHOTO-2021-02-04-20-28-18.jpg)


**Resetting password:**

![img_3.png](PHOTO-2021-02-04-22-35-33.jpg)
![img_3.png](PHOTO-2021-02-04-22-35-26.jpg)

**Home Page**

![img_3.png](PHOTO-2021-02-04-20-33-16.jpg)


Sign-in to **student's page**:

![img_3.png](PHOTO-2021-02-04-20-29-27.jpg)

Sign-in to **instructor's page**:

![img_3.png](PHOTO-2021-02-04-20-34-28.jpg)


**Showing upcoming tasks:**

![img_3.png](PHOTO-2021-02-04-20-31-05.jpg)

**Showing task descriptions:**

![img_3.png](PHOTO-2021-02-04-20-31-41.jpg)


**Making an assignment:**

   Ability to submit test cases, and their corresponding expected output.
   
Ability to make a task, auto-grade and preview students' submissions.



![img_3.png](PHOTO-2021-02-04-20-35-21.jpg)
![img_3.png](PHOTO-2021-02-04-20-34-51.jpg)





## Running the tests

For testing you can use the following input cases and corresponding outputs to apply
on smaple student submissons (python files from the folder tests):
 ```
    input_arith_op="""15, 3
    1,4"""
    add_out ="""18
    5"""
    files to test: add.py, addWrongPartially.py
```

```
    input_arith_op="""15, 3
    1,4"""
    subtract_out ="""12
    -3"""
    files to test: subtract.py
```
```
    input_arith_op="""15, 3
    1,4"""
    divide_out = """5
    0.25"""
    files to test: divide.py
```
```
    input_arith_op="""15, 3
    1,4"""
    multiply_out = """45
    5"""
    files to test: multiply.py
```
```
    input_str_manpulation = "test, 7111"
    output_first_letter = """t
    7"""
    files to test: first_letter.py
```
```
    input_str_manpulation = "test, 7111"
    output_multiply_word = """testtesttesttesttest
    71117111711171117111"""
    files to test: multiply_word.py, multiply_wrong.py
```


## Authors

* **Omar Bahaa**
* **Maria Gamal**
* **Lamiaa Samir** 
  *Initial work*



## Acknowledgments

* Hat tip to anyone whose code was used or gave us inspiration

  [1] https://flask.palletsprojects.com/en/1.1.x/patterns/fileuploads/

  [2] https://www.w3schools.com/tags/tag_a.asp

  [3] https://getbootstrap.com/

  [4] https://flask-sqlalchemy.palletsprojects.com/en/2.x/models/

  [5] https://wtforms.readthedocs.io/en/2.3.x/fields/#wtforms.fields

  [6] https://github.com/CoreyMSchafer/code_snippets/tree/master/Python/Flask_Blog
