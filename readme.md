# Simple Express/MongoDB CRUD API

Wrote this on my own time to intro persistence and database using MongoDB to the software engineering bootcamp I teach at. Extends previous lessons on server side using Node/Express. Local Mongo Community Edition (not Atlas) database seeding using `./data/companies.json`. See `./server.js` for main code.

The class is brand new to coding so it is written as such. Things like error handling are not included. The purpose and focus was starting to build their first CRUD API.

Links to various online resources and notes are included in comments throughout files.

### Setup

Create local DB using Mongo Compass. Ours is called Job Ninja but you can change the `.env` to whatever you'd like. Otherwise standard `npm install` followed by `npm start`. Uses `nodemon` to run server and restart on changes.

### Endpoints

- GET `/` (includes basic sorting)
- POST `/companies/add`
- PATCH `/companies/update`
- DELETE `/companies/delete`
