# databaseproject
Reading and Wrting to the Database

# Environment Setup

```
step 1: Create Environment ...conda create --name (environment name)  python=3.9 -y
step2: Activate the environment
step 3:Install required packages... pip install jupyter sqlalchemy pandas matplotlib pymysql psycopg2-binary pyodbc
```
# Credential

You need to put your credential in json file and save it in this format;
```
{
    "host": "hostname",
    "port": portnumber, 
    "database": "database name",
    "username": "username",
    "password": "password"
}
```