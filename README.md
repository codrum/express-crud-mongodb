# express-crud-mongodb
This node.js app allows for the very basic CRUD operations

- create an event
- edit events
- delete events

## Requirements

* Node 8
* Git

## Common setup

Clone the repo and install the dependencies.

```bash
git clone https://github.com/codrum/express-crud-mongodb.git
cd express-crud-mongodb
npm install
```

## Steps for DB access

Create a .env file in the main directory with the following properties

```bash
MONGODB_CLUSTER_NAME="promineoweek12"
MONGODB_USER="admin"
MONGODB_PASSWORD="WP8XicaVvMYXPlvL"
```

To start the express server, run the following

```bash
node app.js
```

