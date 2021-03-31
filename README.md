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

ESLINT errors

/home/cristian/workspace/full-stack-open-pokedex/app.js
5:14 error 'process' is not defined no-undef
✖ 1 problem (1 error, 0 warnings)

==> add : node": true, in .eslintrc.js
"env": {
"browser": true,
"es6": true,
"jest/globals": true,
"node": true,
},
