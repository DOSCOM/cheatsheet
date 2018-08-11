# cheatsheet

# Node JS

## Deploy with pm2

install
`npm i -g pm2`

list running 
`pm2 list`

start app
`pm2 start path/to/app.js --name app-name` -> app-name that will display in list

display log
`pm2 logs id --line 400`


# Mongo console

## Add user to a database

create your db -> `use applicationdb;`

create user for your db -> `db.createUser({'user':'appuser', 'pwd':'', roles:['readWrite']});`

or with readonly acces -> `db.createUser({'user':'appuser', 'pwd':'', roles:['read']});`
