# XMeme

> XMeme is a simple CRUD application which allows the user to share memes with everyone that they find funny.


![Xmeme (1) (2)](https://user-images.githubusercontent.com/42516515/107529832-4d157e80-6be1-11eb-9cf3-2f96e6db9477.gif)

## Folder Structure
    .
    ├── controller                   # Main logic of the backend
    ├── model                        # Meme Schema
    ├── public                       # Contains static files like CSS
    |    ├── css                     # All the CSS files 
    ├── routes                       # All the routes for GET, POST, PATCH and DELETE
    ├── views                        # EJS files with all code for frontend
    ├── .gitignore
    ├── app.js                       # Entry point of the app
    ├── package-lock.json
    ├── package.json
    └── README.md


MVC architecture patter is used while developing the website and comments have been added properly to differentiate 

#### Built With

- [Node JS](https://nodejs.org/en/)
- [Express JS](https://expressjs.com/)
- [Mongodb](https://www.mongodb.com/)
- [EJS](https://ejs.co/)

## Installation
For Ubuntu

#### Clone Project

```shell
git clone https://github.com/Manthan109/XMeme.git
```

#### Running the project

```shell
cd XMeme\
chmod +x test_server.sh
./test_server.sh
```

## Database

MongoDB used as Database.

## Deployment

Heroku
https://damp-river-68338.herokuapp.com/

