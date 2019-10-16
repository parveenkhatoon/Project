What is Middleware? 

It is those methods/functions/operations that are called BETWEEN processing the Request and sending the Response in your application method.

1:- path

=> path is a module provide a way of working with files and directories paths.

Syntax:-

var path = require('path');


2:- cookie-parser
cookies are small files/data that can store information of a user on their machine.

For using cookies I have to use express middleware that is cookies-parse.
Syntax:-

var cookieParser = require('cookie-parser');
var cookie = cookieParser() => use as a function.



3:- Express.json()

Express.json() is middleware for incoming request should be json object.
Use:- with post and put.
Not Use:- get and delete

Syntax:- 

app.use(express.json());

4:- Express.urlencoded():-

It is a middleware for incoming request should be arrays and strings.

Use:- Post and put
Not use :- get and delete



5:- path.join(__dirname, 'public')

path is a module provide a way of working files and directories from path here I am useing join function which will help to Join several segments into one path


