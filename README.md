# Welcome to Flights Service

## Project Setup
- Clone the project on your local
- Execute `npm install`
- Create `.env` file in the root directory and following environment variable 
-    `PORT=3000`

- Inside the `src/config` folder create a new file `config.json` and add the following piece of json
```
{
  "development": {
    "username": <YOUR_DB_LOGIN_NAME>,
    "password": <YOUR_DB_PASS>,
    "database": "Flights_Search_DB_DEV",
    "host": "127.0.0.1",
    "dialect": "mysql"
  }
}

```
- Once you have added the db config as listed above, go to src folder in your terminal and execute 
`npx sequelize db:create`