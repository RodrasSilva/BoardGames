## Board Games API and Web Application

The Board Games Web Application was built for a project in the Programming in the Internet course in ISEL.
Developed this project with [Rui](https://github.com/RuiPacas) and [Margarida](https://github.com/MargaridaNunes) during my course.

Manage your own board games groups, edited them, create your own user and more.

Web API built using Node Runtime enviromment, express module, request-promise module, async/await, passport.

Web Application built using HTML, CSS, BootStrap Framework, Handlebars, Fetch API and Webpack.

The API Documentation can be found [here](https://github.com/RodrasSilva/BoardGames/wiki/Board-Games-API-Documentation).

### How to run the App  

To run the application you will need :
- Elasticsearch (https://www.elastic.co/downloads/)
- Webpack 
  - webpack     : npm install -g webpack
  - webpack-cli : npm install -g webpack-cli

Follow these steps to run the app : 

1. Run ElasticSearch
2. Open an terminal window in the project directory
3. Run : `curl -X DELETE "localhost:9200/groups?pretty"` in the command line
4. Run : `curl -X DELETE "localhost:9200/users?pretty"` in the command line
5. Run : `npm install` 
6. Run : `npm start` ou `npm run start`
7. Open another terminal in the folder `.../{projectDirectory}/app`
8. Run : `npm install`
9. Run : `webpack -w`

Both the Server and Client are running in the port 8080