# burger
# Eat-Da-Burger App

## Overview
Eat-Da-Burger App is an app that lets users input the names of burgers they'd like to eat by filling out a form and pressing a Submit buton. When the user submits the burger name, the app will display the burger on the left side of the page under a "Burgers available to eat" section. The burgers are then allowed to be devoured. The user can devour it by clicking the "Devour" button, upon which that devoured burger will show up on the right side of the page under a "Burgers Devoured" section.

##Dependencies
* MySQL
* HTML
* Javascript
* Node
* Express
* Handlebars
* ORM

##Getting Started - To install the application follow the instructions below:

```
git clone https://github.com/yaliu8/burger.git
cd burger
npm install
```

## Run the SQL files

* Navigate to the "db" directory.
* Start MySQL command line tool and login: `mysql -u root -p`.
* With the `mysql>` command line tool running, enter the command `source schema.sql`. This will run the schema file and all of the queries in it to create the database.
* Now insert the entries defined in `seeds.sql` by running the file: `source seeds.sql`.
* Close out of the MySQL command line tool: `exit`.

## Running Locally
To run the application locally and access it in your browser, first set the PORT environment variable to the value of your choice. An example is shown below.

```
export PORT=8080
```

After the PORT environment variable has been set, run the Node.js application with the command below.

```
node server.js
```

The application will now be running locally on PORT, in this case that is port 8080. You can then access it locally from your browser at the URL localhost:PORT, in this case localhost:8080.

```

