# Distributed Databases
## Authors:
* ## Cesar Arcos: racec9999@gmail.com
* ## Eduardo Ceja: lalitoceja@gmaill.com
## License :
MIT License
## Introduction:
We create a software that manage two distributed databases
## Requirements:
The proyect needs the following packages, this projects run on linux.:
* Python 3: sudo apt-get install python3.8
* Pyqt5: pip3 install PyQt5
* Pandas: pip3 install pandas 
* MySQL Connector (python version): pip3 install mysql-connector-python
* A Mariadb or MYSQL server running, with tables like the ones in `Moreliadb.sql` and `Patzcuaro.sql`. Alternatively, import the databases, make sure to create the databases beforehand, using `mysql -u <user> -p <database name> <  Morelia.sql` replacing `<user>` and `<database name>` with your SQL user (or Mariadb user) and name of the databse you're going to import to. Other option is to use the sript named `CreateDB.sql` like this `mariadb -u <user> -p < CreateDB.sql`.
## Installation:
Clone this repository and change the file "dbconection.py" with your own mariadb user and password, then you need to create the databases and the tables to save the data, you have all the required queries in the file "CreateDB.sql" then your installation is ready

## Run
Tu run it you need to stay in a terminal at the folder named distributed-database-exercise then type `python3 main.py`
