# Ultimate Strapi Starter application
A strapi application with example of article with category and ratings feature

## NOTE: WORK IN PROGRESS
plan to launch v1 in mid JUNE


## Strapi features which are implemented:

- *Roles & Permissions:*
  - This plugin provides a way to protect your API with a full authentication process based on JWT. This plugin comes also with an ACL strategy that allows you to manage the permissions between the groups of users.
  - *Providers:*
    - Google
- *Upload:* You can upload any kind of file on external providers **AWS S3**
- *GraphQL:* With the GraphQL plugin, you will be able to fetch and mutate your content.
- *API Documentation:* This plugin uses SWAGGER UI to visualize your API's documentation.
- *[COMING SOON]* Custom Plugin
- *[COMING SOON]* Auto Deployment
- *[COMING SOON]* NEXT.js static website


## Setup
### 🖐 Requirements

**Supported operating systems**:
- Ubuntu 18.04/Debian 9.x
- CentOS/RHEL 8
- macOS Mojave
- Windows 10

**Node:**
- NodeJS >= 10.x
- NPM >= 6.x

**Database:**
- PostgreSQL >= 10

### How to Setup Server:
- run `npm i` to install dependencies
- create `.env` to set env variables
- copy all variables from .env.development and set the value
- run `npm run develop` to start development server
- run `npm run build` to build strapi app
- run `npm run start` to start server

To Setup Database
- go to `docs` directory
- run command `docker-compose up -d` using this command you can install postgresql image on docker
