# Setting up a Node Project With Typescript & PostgreSQL

Basic commands to setup a Node Typescript server using PostgreSQL

## Initate node project
`npm init -y`

## Insalling typescript
`npm install typescript --save-dev`

## Initiating typescript 
add to your package.json filer under scripts: `"tsc": "tsc"` before executing the command

`npm run tsc -- --init`

## Installing Express server
`npm install express`

## Installing Eslint and Types Express
`npm install --save-dev eslint @types/express @typescript-eslint/eslint-plugin @typescript-eslint/parser`

## Installing ts-node for dev mode
`npm install --save-dev ts-node-dev`

## Installing Cors for cross development enviroment
For client <> server communication.

`npm install cors`

`npm install --save-dev @types/cors`

## Installing dotenv for accessing .env variables
`npm install dotenv` 

## Installing PostgreSQL and PostgresSQL Types
`npm install pg`

`npm install --save @types/pg`

## Installing Jest & Supertest for Integration testing
`npm install --save-dev jest`

`npm install supertest --save-dev`

## Configuring Jest & Suptertest for typescript
`npm i -D jest typescript`

`npm i -D ts-jest @types/jest`	

`npx ts-jest config:init`	

`npm install --save @types/supertest`

## Installing and opening Cypress for End-to-End testing
`npm install cypress --save-dev`

`npx cypress open`
