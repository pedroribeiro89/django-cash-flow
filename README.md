# django-personal-finance

Project for practice python and django

1. Install dependecies(requeirements) on your virtual env
2. create super user with
    ~~~~ssh
    ./manage.py createsuperuser --username=admin --email=admin
    ~~~~
3. run with
    ~~~~ssh
    ./manage.py runserver
    ~~~~
4. access admin with route http://127.0.0.1:8000/admin and add 
    Expenses and incomes classifications, payment methods, incomes and expenses
    
5.  Routes:  
    * Income Report: http://127.0.0.1:8000/incomes/
    * Expenses Report: http://127.0.0.1:8000/expenses/
    * Expected Cash Flow: http://127.0.0.1:8000/expected-cash-flow/
    * Realized Cash Flow: http://127.0.0.1:8000/realized-cash-flow/