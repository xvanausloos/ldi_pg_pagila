Author: xavier.vanausloos@ladonneeintelligente.com
Creation: 6/03/26

Demo database for Postgres 

# Download the dump
````
wget https://raw.githubusercontent.com/devrimgunduz/pagila/master/pagila-data.sql
wget https://raw.githubusercontent.com/devrimgunduz/pagila/master/pagila-schema.sql
````
# Create the database and import
```
create database pagila
psql -U your_username -d pagila -f pagila-schema.sql
psql -U your_username -d pagila -f pagila-data.sql
````

 
