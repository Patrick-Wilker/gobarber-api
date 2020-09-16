<h1 align="center"><strong>GoBarber API</strong></h1>

<h2> <img src="https://user-images.githubusercontent.com/38691922/77790815-3d7e5d00-7044-11ea-8ffe-e8d448946d4a.png" height="30" width="30">About the project</h2>

This api provides everything needed to organize appointments between the barbers and customers.

Customers can choose the best time available to them.

<h2><img src="https://user-images.githubusercontent.com/38691922/77791007-98b04f80-7044-11ea-9602-4c78098960a0.png" height="40" width="40"> Technologies</h2>

* Node.js
* Express
* Sequelize
* Multer
* Yup
* JWT-token
* PostgreSQL
* Date-fns
* Nodemailer
* Mongoose
* Bee Queue
* Sentry

<h2>Getting started</h2>

Import the Insomnia.json on Insomnia App or click on Run in Insomnia button

<h3>Requirements</h3>

* Node.js
* Yarn or npm

> Obs.: I recommend use docker

<h3>Follow the steps below</h3>

```
# Install the dependencies
$ yarn

# Create the instance of postgreSQL using docker
docker run --name database -e POSTGRES_PASSWORD=docker -p 5432:5432

# Create the instance of mongoDB using docker
docker run --name mongobarber -p 27017:27017 -d -t mongo

# Create the instance of redis using docker
docker run --name redisbarber -p 6379:6379 -d -t redis:alpine

# Create the tables in the database
$ sequelize db:migrate

# Start backend
$ yarn dev

```

With the postgres data (host, port, name, password) connect to Postbird and create a database with the name gobarber
