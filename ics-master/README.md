# ICS Mini-project

The ICS project is broken into 3 subparts: sql-injection, XSS, and XSS secure

## sql-injection

This demonstrates a sql-injection attack.

1. navigate to /sql_injection
2. run <code>$ python3 manage.py runserver</code>
3. go [here](http://127.0.0.1:8000/items/search)
4. type this in search query: ' UNION SELECT first_name FROM auth_user WHERE first_name LIKE ' (with quotes)


