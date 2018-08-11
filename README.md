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

