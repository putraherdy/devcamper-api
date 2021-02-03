# DevCamper API

> Backend API for DevCamper application, which is a bootcamp directory website

## USAGE

Rename "config/config.env.env" to "config/config.env" and update the values/settings to your own

## Install Dependencies

```
npm install
```

## Run App

```
# Run in dev mode
npm run dev

# Run in prod mode
npm start
```

## Database Seeder

To seed the database with users, bootcamps, courses and reviews with data from the "_data" folder, run

```
# Destroy all data
node seeder -d

# Import all data
node seeder -i
```

## Demo

Documentation with examples [here] (https://documenter.getpostman.com/view/10434883/SzRz1A87)

- Version: 1.0.0
- License: MIT
