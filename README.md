# ECommerceBackend

## Description
Sequelize is used with mySQL, served by Express.js as the server-backend to use a database of products, with categories and tags.


## Technologies Used
- Node.js
- Express.js
- mySQL
- Sequelize, an 'npm' package


##  Installation and Setup Instructions
- navigate to the main folder... the one with "server.js" and "package.json"
- at the prompt, install node dependencies, with "npm i" (without the quotation marks)
- at the prompt, initialize the database schema, with mySQL, with "mysql -u {username} -p" ... and then type in your password when prompted
- at the mySQL prompt, initialze the database schema, with "source db/schema.sql"
- at the mySQL prompt, exit the mySQL prompt, with "\q"
- at the terminal prompt, seed the database, with "npm run seed"
- at the terminal prompt, run the server, with "npm start"
- open Insomnia, navigate to the path:  "http://localhost:3001", and you can GET, POST, PUT, and DELETE from there


## Video Demos
- Install and Prepare to Run:  <br>  https://drive.google.com/file/d/1jBKx3bMaAmEK1cxUF6EFMn2jKXWc33Kb/view
  <br>    <br>  
- GET all Categories, Products, and Tags:   <br>  https://drive.google.com/file/d/1ZQeqQ5mB1JrokfSC2JFQHn7I4RQmU19M/view
  <br>    <br>  
- GET specific Categories, Products, and Tags by ID#:  <br>  https://drive.google.com/file/d/1joAKQAK5EvjnPnKelJtOqipwOKbDyVtb/view
  <br>    <br>  
- POST (create) a Category:  <br>  https://drive.google.com/file/d/1kFVIzy2jLK3SmnEh7RYVyeiOly4l2TX_/view
  <br>    <br>  
- POST (create) a Product:  <br>  https://drive.google.com/file/d/1PHr745tH6qIlZepYq6fMIcCrHO6ysKs4/view
  <br>    <br>  
- POST (create) a Tag:  <br>  https://drive.google.com/file/d/1kdTT5n9L5EasZCF4bt_sOyvkvlW-nOrH/view
  <br>    <br>  
- PUT (update) a Category:  <br>  https://drive.google.com/file/d/1B3BnZRIzbqBpIbTBnVgsTHDQmKiU_wPB/view
  <br>    <br>  
- PUT (update) a Product:  <br>  https://drive.google.com/file/d/1E3B1_jKNVkuEDQqP7wJRBDq_1e1_blP6/view
  <br>    <br>  
- PUT (update) a Tag:  <br>  https://drive.google.com/file/d/1E3B1_jKNVkuEDQqP7wJRBDq_1e1_blP6/view
  <br>    <br>  
- DELETE (destroy) a Category:  <br>  https://drive.google.com/file/d/1E3B1_jKNVkuEDQqP7wJRBDq_1e1_blP6/view
  <br>    <br>  
- DELETE (destroy) a Product:  <br>  https://drive.google.com/file/d/10QIRLFNiNJ64cDB_vMfVL_s7aRzpw7d_/view
  <br>    <br>  
- DELETE (destroy) a Tag:  <br>  https://drive.google.com/file/d/1kec3PIfeZwPloOsGtjlx3zfBWytmVr44/view
  <br>    <br>  