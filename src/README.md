# Overview

This project structure uses the AdonisJS API framework. It sets up an API server that has separate front-end and back-end projects, with Adonis as the back-end

Ref: https://adocasts.com/series/lets-learn-adonisjs-5/lessons/lets-learn-adonis-5-creating-new-project

## Usage

1. Ensure both below are installed on your computer:
- NodeJS version 14.15.4 or greater
- NPM version 6.0.0 or greater

- check this with node -v and npm -v

2. From folder where project is saved, use [ npm run dev ] to launch the project

3. From Postman or equivalent, send a GET request to http://127.0.0.1:3333

- path options are included in ./start/routes.ts

## Ace CLI

1. Within the terminal in the project folder, enter [ node ace ]

2. This will give a list of command options for building and testing the project outside of the IDE

3. Useful examples:
- [ node ace -v ] to find version
- [ node ace serve ] to start the server
- [ node ace serve -h ] to discover flags to use with serve
- [ node ace list:routes ] to see route paths