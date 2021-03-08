# expenses_tools
Objective: Projext expentrac allows a user to login and track her expenses in no particular order for record keeping.

Features included:

Login and logout(authentication)
Creation of expense records
Updating expense records
Deleting expense records
Filtering by month of expense
Filtering by category of expense
A total expense calculator after each expense line, which cumulates the expense values of all expenses
Some of the system used for this are:

Django authentication system with error handling for forms
PyPi project for django bootstrap modal forms: https://pypi.org/project/django-bootstrap-modal-forms/
Bootstrap for table styling and modal
Standard date-picker for forms
Things to implement for the future:

Filter fixes when both month and category filters are applied
Pagination of results
Total calculation to match the currently-shown expense results (for this, filtering must occur on the server)
Column sorting
Filter months to be in order
Ability to add custom category
To run the project:

Start a virtual environment (venv) after cloning the repo
Do a 'pip install' to install the dependencies of the requirements.txt
Once that is done, run project using 'python manage.py runserver'

Author : 
Name : Sayeed Hossain
Mail : sayeedhatim@gmail.com