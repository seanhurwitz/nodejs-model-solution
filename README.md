# NODEJS MODEL SOLUTION

## Requirement

Trackmatic's client structure is as follows: The client is a GROUP (consider Massmart) which may have one or more ORGANISATIONS (consider Makro, MassBuild, Fruitspot) which in turn have one or more SITES (Woodmead, Germiston, Centurion). The solution builds the basic database structure for the GROUP, ORG, and SITE tables using NodeJS and MySQL.

---

---

## Setup

Ensure NodeJS and NPM are installed on your device.

Ensure Docker is running and launch an instance of MySQL, using kitematic or running this in the terminal:

`docker start mysql-connect || docker run --name mysql-connect -p 3306:3306 -e MYSQL_ROOT_PASSWORD=P@ssw0rd -d mysql:latest`

Open up a terminal in the root of the project and run:

- `npm i`
- `npm run dev`

Ensure you receive all TRUE for the test suite printed to the terminal.

Enjoy!
