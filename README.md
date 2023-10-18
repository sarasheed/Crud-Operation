# Crud-Operation
create, read, update, and delete operations in angular 4


Create an Angular project by typing these commands in CMD(windows)/Terminal (Linux)
1) npm install -g @angular/cli
2) ng new my-app
3) cd my-app
4) ng serve --open

install Json-server with this command 

npm install -g json-server


then Create an empty file in the same folder where angular is installed with file.json
and write the data that you want to show on your json server

for example:


[
  {
    "id": 1,
    "name": "t-shirt",
    "color": "red"
  },
  {
    "id": 2,
    "name": "trouser",
    "color": "yellow"
  },
  {
    "id": 3,
    "name": "hat",
    "color": "blue"
  },
  {
    "name": "kurta",
    "color": "black",
    "id": 4
  }
]

then save the file and Run Json-server with this Command

json-server --watch file.json

