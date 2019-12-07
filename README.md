# WSMS (Wildfire Sensor Management System)
This is a web application focused on relational databse for CMPE226 course project 2.
There are three components in this repo:
- WSMS (client side)
- WSMS_server (server side)
- sql_script (database)

# Tech/framework used
Framework: React JS, Express.js, Node.js
Database engine: MySQL
Language: JavaScript

# Getting started
The following instructions are for macOS.

## Requirements
### Homebrew
Please install Homebrew if it's not already done with the following command:
```
$ ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"
```
You should be able to run the following command after the installation procedure below:
```
$ brew -v
Homebrew 2.2.0
```
### Node
You should be able to run the following command after the installation procedure below:
```
$ node --version
v10.15.0
$ npm --version
6.13.1
```
Otherwise, run the following command to install Node:
```
$ brew install node
```

## Installation
To get the application running locally:
- clone this repo
- Run all scripts in sql_script in MySQLWorkbench
- Go to WSMS_server, then run:
```
$ nodemon index.js
```
- Go to WSMS, then run sequentially:
```
$ npm install
$ npm start
```
Local web server will use port 4000, for example:
http://localhost:4000/dashboard
