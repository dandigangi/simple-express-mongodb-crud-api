# Simple Express MongoDB Crud API

Wrote this on my own time as an intro to MongoDB as a database. Extends previous lessons on server side using Node/Express. Local database seeding using the ` companies.json`` file in  `/data`.

### Setup

Create local DB using compass. Ours is called Job Ninja but you can change the `.env` to whatever you'd like. Otherwise standard `npm install` followed by `npm start`. Uses `nodemon` to run server and restart on changes.

### Endpoints

- GET `/` (includes basic sorting)
- POST `/companies/add`
- PATCH `/companies/update`
- DELETE `/companies/delete`
