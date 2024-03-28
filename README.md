![Logo](logo.png)

Thomas Jordan, Thomas Kim, Ewan Shen

References: StackOverflow regarding linking HTML pages and flask implementation among other imports and issues. ChatGPT for helping us debug our code.

# SmallSIEM
A simple SIEM written in Python using a MySQL backend.
SmallSIEM supports the storage and interactions between users, IP addresses, locations, and events
Implements a database using MySQL, Flask, Jinja2, HTML, Python.
SQL File in Setup


## Installation
To setup the database, run:
- `pip install -r requirements.txt`
- `mysql -u root -p < Setup/setup.sql`
- `python3 Setup/fill_db.py`
Then to setup the webapp:
- `python3 SmallSIEM/app.py`
