# Angular CRUD Project with Node.js Backend

This project is a simple application that demonstrates CRUD (Create, Read, Update, Delete) operations with an Angular frontend and a Node.js backend.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [Angular Development Server](#angular-development-server)
  - [Node.js Server](#nodejs-server)
  - [API Endpoints](#api-endpoints)
- [Features](#features)
- [Folder Structure](#folder-structure)
- [Technologies Used](#technologies-used)
- [License](#license)

## Getting Started

### Prerequisites

Make sure you have the following installed before running the project:

- [Node.js](https://nodejs.org/) - Node.js and npm are required to run both the Angular frontend and the Node.js backend.
- [Angular CLI](https://cli.angular.io/) - Install Angular CLI globally.

### Installation

1. Clone the repository:

   ```bash
   git clone git@github.com:mansoorfaizi/Angular-CRUD-project.git


### Angular Development Server
- cd shope
- npm install
- ng serve


### Node.js Server
- cd server
- node server


### API Endpoints
- Create: POST http://localhost:4200/api/clothes
- Read: GET http://localhost:4200/api/clothes
- Update: PUT http://localhost:4200/api/clothes/:id
- Delete: DELETE http://localhost:4200/api/clothes/:id

## Folder Structure
angular-CRUD-project/
|-- src/
| |-- app/
| | |-- components/
| | | |-- edit-popup/
| | | |-- product/
| | |-- home/
| | |-- layout/
| | | |-- footer
| | | |-- header
| | |-- services

|-- backend/
| |-- server.js
| |-- db.json/

|-- ...
|-- README.md
|-- package.json
|-- angular.json
|-- ...


## Technologies Used
- TypeScript
- PrimeNg
- node js
- Angular


## License

This project is licensed under the [GNU General Public License (GPL)](LICENSE).
