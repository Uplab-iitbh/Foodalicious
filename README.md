# Foodalicious
This website is a simple food ordering system written in Django.  The Online Food Ordering System(FoodAlicious) is a website has a food ordering website for a customer and a separate website for order retrieval system for Restaurant.

The options available to the Customer are view menu, create an order and checkout.

![image](https://github.com/Uplab-iitbh/Foodalicious/assets/150852361/79d87214-f8b2-420a-9bb3-1461c57cb38e)


## Features

- Authentication system
- Customers can select the menu, Add/remove items and can make payment online (future scope).
- Data stored in a sqlite3 database
- Friendly user interface
- Users can view a list of food items available for order.
- Users can place an order for the items if they select.

Django supports normal and admin privileged users.

## Admin only Features
- Admins can add, edit, or delete food items and food types in the system.
- Admins can view the user's order.
- Admins can view the order history of all users.

## Prerequisites
- Basic understanding of Python programming language.
- Familiarity with Django web framework.

## Technologies
### Frontend
- HTML, CSS, javascript, BootStrap

### Backend
- Python, Django, sqlite3

## Tables
There are several classes that inherit Models from Django in order to create tables.

These classes are Food Category, Food Details, Customer Details, Customer Order Selection and Customer Order Status.

The table names and columns are created in the database by Django when the app initially starts and a connection is also made to the database by Django's internal functions.

## Purpose of the table
The purpose of the tables in the database is to store records when the customer performs a certain activity.

For example - When the customer will view the menu, so they will be able to see these items.
## How to run locally:

## Run Locally

Clone the project

```bash
  https://github.com/Uplab-iitbh/FoodAlicious.git
```

Activate Django Environment
```
DjangoEnv/Scripts/Activate
```
Run Server
```
>> python manage.py runserver
Watching for file changes with StatReloader
Performing system checks...

System check identified no issues (0 silenced).
February 11, 2020 - 12:48:34
Django version 3.0.2, using settings 'foodorderingsystem.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.
```
