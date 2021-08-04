# Mental App
Backend for Mental App from UET
## Getting Started

Follow these instructions to set up this project on local machine.

### Prerequisites

- [Install node](https://nodejs.org/en/download/) and it will also install npm.
- After that, install yarn.

  ```
  npm install -g yarn
  ```

  then check it

  ```
  node -v

  // v14.3.0

  yarn -v

  // 1.22.4
  ```

### Installing
- Install dependencies
  ```
  yarn
  ```
- Create database (change host/pass db in config file)

  ```
  sequelize-cli db:create db:migrate db:seed:all
  ```
- Run project
  ```
  yarn start
  ```

### run
- Install
  ```
  node v14.3.0
  yarn 1.22.4
  npx 6.14.11
  ```
- Setting environment
  ```
  cp .env.example .env
  change DATABASE_URL with database url on production in .env file
  ```
- Migrate DB
  ```
  npx sequelize-cli db:migrate
  npx sequelize-cli db:seed:all
  
  <!-- test pool v2
  npx sequelize-cli db:seed --seed v2_test_pool.seed.js -->
  ```
- Run
  ```
  yarn start
  ```