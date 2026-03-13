[![Deployment Pipeline](https://github.com/midudev/pokedex-for-ci/actions/workflows/pipeline.yml/badge.svg)](https://github.com/midudev/pokedex-for-ci/actions/workflows/pipeline.yml)

# Full Stack open CI/CD

This repository is used for the CI/CD module of the Full stack open course

Fork the repository to complete course exercises

## Commands

Start by running `npm install` inside the project folder

`npm start` to run the webpack dev server
`npm test` to run tests
`npm run eslint` to run eslint
`npm run build` to make a production build
`npm run start-prod` to run your production build


Add to linux

export NODE_OPTIONS=--openssl-legacy-provider

in powershell 

$env:NODE_OPTIONS = "--openssl-legacy-provider"

Manualmente creando un workflow 
Crea un folder .github
Inside un folder workflows

Create a  yml file to have the workflow

