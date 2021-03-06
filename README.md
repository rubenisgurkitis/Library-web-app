# Library
Library single page web app, fed with mock data using json-server.

####Requisites to run the app
To install all dependencies you will need to have installed *npm*. First, you will need to install *Node.js* and after that, run the following command to ensure that you are using an updated version of *npm*
```
> sudo npm install npm -g
```
With this, everything should be ready for running the app with the command *gulp*, but sometimes it can give some errors on Windows machines. In this case, a solution can be found in this [stackoverflow post](http://stackoverflow.com/a/24042936).

####How to run the app

Checkout this repo
```
> git clone https://github.com/rubenisgurkitis/Library.git
```
Browse to the root folder
```
> cd Library
```
Install dependencies
```
> npm install
```
Start the mock server
```
> json-server --watch db.json
```
Start the gulp process
```
> gulp
```
Once the build is finish, open a new tab or terminal and:
```
> gulp webserver
```
The default browser will open automatically!!
