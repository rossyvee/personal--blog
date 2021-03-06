# Personal-Blog
An application that allows users to share thoughts through blogging and make comments about other authors or bloggers posts

## Table of Content
+ [Description](#description)
+ [Installation Requirement]( Requisites)
+ [Technology Used](technology-used)
+ [Live links](#Live links)
+ [Reference](#reference)
+ [Licence](#licence)
+ [Authors Info](#aut)

## Description
An application that allows users to share thoughts through blogging and make comments about other authors or bloggers posts

## Technology Used
* [Python3.6](https://www.python.org/)
* [Flask](http://flask.pocoo.org/)
* [Heroku](https://heroku.com)
## Requirements
* A stable internet connection
## User Story
* Comment on the different blog posted by other user.
* See the blogs posted by other users and allow others to comment.
* Allows other users to sign up for notifications
* Register to be allowed to log in to the application
## set up instruction and installation
 1. clone this repository to a folder https://github.com/rossyvee/personal--blog
 2. Extract the cloned file and install requirements
* cd the folder then open the personal blog
* pip install -r requirements.txt
  3. Export configurations
  4. python3 -m venv virtual --without-pip
# Running the application locally

source virtual/bin/activate

pip install -r requirements.txt

alternatively run (make sure the virtual environment is activated)

python3 manage.py 

## Behaviour Drive and Development
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Load the page  |Select between signup and login|
| Select SignUp| **Email**,**Username**,**Password** | Redirect to login|
| Select Login | **Username** and **password** | Redirect to page with the create blog based on categories and commenting section|
| Select comment button | **Comment** | Form that you input your comment|
| Click on submit |  | Redirect to all comments template with your comment and other comments|

  ## Licence
MIT License
Copyright (c) [2022] [Roseline Akinyi]
Permission is  granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE
## Authors Info
Slack Profile - Rose Akinyi.

LinkedIn - (Roseline Akinyi: https://www.linkedin.com/in/roseline-akinyi-065875895/)

Email - roseakinyi001@gmail.com



