# ADSS: Cryptocurrency Information Web and API
### By Marcela Funabashi, Cloe Chapotot, & Jean Carlos

## 1. Project Description
This is an assignment for our Advanced Data Structures and Storage class, which involves creating a simple web that displays information for several cryptocurrencies.
It has 2 main functions:
1. Allow users to manually search for a cryptocurrency through its name or ticker, or to choose from a drop down menu.
2. Provide a few relevant information the chosen cryptocurrency in another page once it is chosen by the user.

### Technologies Used:
This assignment was developed through a free account in PythonAnywhere with Python version 3.10.

## 2. Prerequisites
### Development Environment:
A free version of a PythonAnywhere account was used. It contains Python version 3.10.
### Libraries:
This program is making use of the Flask, Pandas, TinyDb and OS libraries/frameworks.
To avoid any issues with installation, the following commands can be run in the Bash Console in PythonAnywhere before running the flask_app.py content:
```
python -m pip install flask
python -m pip install pandas
python -m pip install tinydb
python -m pip install os
```
## 3. Installation:
1. The first step is to download the zip file in this Github. This zip file will include the README, the flask_app.py code file, the index.html file, and the supporting dataset required to run the code.
2. Upload the flask_app.py file and the 'Cryptocurrencies.csv' dataset into the mysite directory within PythonAnywhere.
3. Upload the index.html file into the templates directory, within the mysite directory, within PythonAnywhere.
## 4. Use
1. Change the file path to the 'Cryptocurrencies.csv' dataset within the flask_app.py code file according to your file path.
2. Save and reload all files, so as to make sure everything is working.
3. Access web through your PythonAnywhere site (example: http://mfunabashi.pythonanywhere.com/ )
## Important Note:
* An initial attempt was done to create a database through MongoDB and connect in PythonAnywhere. However, PythonAnywhere free accounts can only make HTTP or HTTPS connections to a specific set of whitelisted sites, and MongoDB uses its own protocol that is not HTTP/HTTPS. Thus, TinyDB was used as the NoSQL source.
