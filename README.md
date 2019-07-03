# Rails_suscribers

A simple Ruby on Rails app to collect email signups and save them into a database. At the bottom of the page, when a user enters his email, the email is saved into a database.

## How it works

In the first turn of the request/response cycle, the signup form is displayed to the user, handling GET requests.
When the user fills in the form with an email and submits it, it triggers the second turn of the request/response cycle, where the email data is saved into the database, handling POST requests.

## About Ruby On Rails

Ruby on Rails is a web framework that makes it easy to build powerful web apps in a short amount of time.
Ruby on Rails is written in the Ruby programming language.


## Prerequisite

* Install or Update Ruby -> https://www.ruby-lang.org/en/documentation/installation/ 

* Install Rails -> http://installrails.com/



## How to run the test suite


In the terminal, type **rails server**

While it's running, to check the database, do the following:
	
		• In the terminal, open a new tab 
		• Switch into your app’s folder
		• Start the Rails console by running **rails console**
		• When you enter the Rails console, retrieve all emails in the database by running the query **Signup.all**
		• This query returns all emails in the database as an array. Your email should show up in the console output. To exit the Rails console at any point, use Ctrl+D.


