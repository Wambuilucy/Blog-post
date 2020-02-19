# Blogs

Bussiness-Online

## Author
Lucy Wambui Kinyanjui.

## Description
This web application allows users to order products of their choice by listing the products then sending the order to the bussiness owner.
Features
As a user:
You can create account,login,signup

You can view products

3.You can order by listing the products in the form

## BDD
Behaviour	input	Output
View all products	Bussiness page displays all products	Bussiness page displays all products
View all products	Home page displays lista of products	Home page displays all list products
login	Click on login	allows user to login into the account using the login form
create an account	Click on sign in	form which allows users to sign in for the first time
List products	Click on new order	brings an input form for listing products
update/delete	Click on update/delete	can updatedor delete the list
## Technology used
* python3.6
* Flask
* Bootsrap
* HTML5
* CSS3

# Requirements
 The following command installs all the application requirements

   pip freeze -r requirements.txt

## User stories 

* As a user,I would like to view the blog posts on the site
* As a use,I would like to comment on blog posts
* As a user,I would like to view the most recent blog posts
* As a user,I would like to see an email alert when a new post is made by joining a subscription.
* As a user,I would like to  see random quotes on the site.
* As a writer,I would like to sign in to the blog.
* As a writer,I would like to create a blog from the application.
* As a writer,I would like to delete comments that I find insulting or degrading.
* As a writer,I would like to update or delete blogs I have created.

## Installations
 Run git clone https://github.com/Wambuilucy/blogs.git or download the zip file from github.

 After extracting the files,
1. Navigate to the project folder

  cd blogs.

2. Create a virtual enviroment

   virtualenv virtual.

3. Activating the virtual enviroment
    
    source virtual/bin/activate.

4. Running the application
    
    python3 manage.py server

5. Running tests
   
   pythone3 manage.py test.
   
## Running the application

Modify the start.sh file with your own api key. To run the app type the commands in your terminal install all the dependencies listed in the requirements.txt file

$ chmod a+x start.sh

$ ./start.sh

Testing the appication
To run the tests for the class in your terminal

$ python3.6 manage.py test

# Known Bugs
The side bar is not functioning
Future implements
The customer, to see the history of all the purchases he/she.
Business owner,to see a list of all the sales have made.
Business owner,to see the total amount of sales have made.
Customer,to receive an error message if tried to purchase a product that’s out of stock.
# Contacts
For more information : wambuilucie99@gmail.com

# Github live link
 github.com/wambuilucy/blog-post

# Licence
This project is Licensed under MIT. ©2019 Copyright.