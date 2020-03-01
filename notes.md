Before testing the website framework first run a database migration. This updates our database to include any models in our installed applications (and removes some build warnings).

Django uses an Object-Relational-Mapper (ORM) to map model definitions in the Django code to the data structure used by the underlying database
You should re-run migrations and re-test the site whenever you make significant changes

A view is a function that processes an HTTP request, fetches the required data from the database, renders the data in an HTML page using an HTML template, and then returns the generated HTML in an HTTP response to display the page to the user

You can easily recognise template variables and template tags (functions) - variables are enclosed in double braces ({{ num_books }}), and tags are enclosed in single braces with percentage signs ({% extends "base_generic.html" %}).
