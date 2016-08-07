we are converting the CSV File to JSON format and creating the httpserver using http module of nodejs.org

-->Install Node.js


How to run your own server :

--> open cmd (at same project location)
-->npm init (than it'll ask some questions)

name : (show the current folder where you are) application name(optional) (all must be in lower case) <-- (enter)

version : (default) <--(enter)
description : if any <--(enter)
entry point : (auto pic js file) write your.js file if it's diffrent
test command: node jsfilename.js
/*
if you don't want to restart your server everytime to apply changes 
so in test command we have to use nodemon jsfilename.js insted
test command: node jsfilename.js

eg: test command: nodemon jsfilename.js
*/
git repository: <--(enter)

all enter and u'll get the package.json file at same location

than check your json code on jsonlint.com


now we'll get the script object in json file and use the particular object name to run server

open Cmd <--

--> npm start/test (server started)

than paste that link in browser
http://localhost:8080/index.html


