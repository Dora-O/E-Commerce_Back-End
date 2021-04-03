# E-Commerce_Back-End
Modified starter code to create an application called E-Commerce Back End that can be used get, post, put and delete categories, products and tags. 

Built the back end and connected it to the starter code (front end).

Configured a working Express.js API to use Sequelize to interact with a MySQL database.

User will need to create a .env file and input their user and password info like the following:
DB_USER=root
DB_PW='userpassword'
DB_NAME='ecommerce_db'

User will need to use MySQL for the schema and command line to seed database.

User will then use 'npm start' to run server.

User will use Insomnia application to:
- Get localhost:3001/api/categories
- Get localhost:3001/api/products
- Get localhost:3001/api/tags

User will also be able to post, put and delete to categories, products and tags.

## Dependencies
- Express
- MySQL/MySQL2
- DotEnv
- Sequelize

## Link to walkthrough videos
[Initial Set-up](https://youtu.be/Lv1RJfxA_Kc)
[Get, Post, Put & Delete](https://youtu.be/rn7QF4rh-6I)

## Screenshots:
<img src = "https://user-images.githubusercontent.com/70343136/113466918-20bdf780-9405-11eb-9d61-c2af77a0b370.png">
<img src = "https://user-images.githubusercontent.com/70343136/113466919-21ef2480-9405-11eb-88de-55fae8237f2c.png">
<img src = "https://user-images.githubusercontent.com/70343136/113466921-2287bb00-9405-11eb-9b06-6885cceddc7f.png">