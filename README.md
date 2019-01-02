# stackoverflow-api


- StackOverflow-api is a platform where people can ask questions and provide answers.

# Features
- Users can create an account and log in. 
- Users can post questions. 
- Users can delete the questions they post. 
- Users can post answers. 
- Users can view the answers to questions. 

# Tools Used
- `Python2.7` - A High Level Programming Language
- `Flask` - Python based web framework
- `Pytest` - A Python testing  framework which makes it easy to write small tests, yet scales to support complex functional testing for applications and libraries
- `Virtualenv` - A tool to create isolated virtual environment
- `Postgresql` - PostgreSQL is a powerful, open source object-relational database system.

# Running the tests
To run tests run this command below in your terminal

```

```

# Installation
**Clone this _Repository_**
```
$ https://github.com/exdus/stackoverflow-api.git
$ cd stackoverflow-api
```
**Create virtual environment and install it**
```
$ virtualenv env
$ source / venv/bin/activate
```
**Install all the necessary _dependencies_ by**
```
$ pip install - r requirements.txt
```
**Run _app_ by**
```
$ Python run.py
$ Run the server At the terminal or console type
```
# End Points


| url/endpoint and methods              | Verb           | Action                  | Parameters     
| ----------------------------------- |:-------------:|  ------------------------- |----------------------|
| /api/v1/auth/signup                   | POST           | User gets registered    | username,email,password |
| /api/v1/auth/login                    | POST           | User login              | username,password |
| /api/v1/questions                     | GET            | fetch all questions     | -   |
| /api/v1/questions/<int:qnId>          | GET            | fetch specific question | <any number as id of question> |
| /api/v1/questions                     | POST           | post a question         | question |
| /api/v1/questions/<int:qnId>/answers  | POST           |answer specific question | answer |
| /api/v1/questions/<int:qnId>          | DELETE         | delete a question       | <any number as id of question>|


# Contributors
- [kelvin Bunei](https://github.com/exdus/)
