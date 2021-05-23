# mysql_tutor
NodeJS, Express, Sequelize, MySQL tutorial

## Config files
Files in config are not in the repository

### config/db.config.js

```javascript
module.exports = {
  HOST: "localhost",
  USER: "user",
  PASSWORD: "password",
  DB: "workout",
  dialect: "mysql",
  pool: {
    max: 5,
    min: 0,
    acquire: 30000,
    idle: 10000
  }
};
```

