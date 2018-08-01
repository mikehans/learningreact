# React and Flux Intro (Pluralsight)

## Packages and versions used in the course
* gulp 3.9.0
* gulp-connect 2.2.0
* gulp-open 1.0.0
* browserify
* bootstrap 3.3.5
* jquery 2.1.4
* gulp-concat 2.6.0



* react 0.13

## Naming conventions
* camelCase.js used here
* could also use *.jsx or something else


## Mock HTTP Requests
Source: Pluralsight - Build a JS Development Environment
Options:
* Nock
    * basic - hardcoded responses
* Static JSON
    * same data every time
    * no changes saved
* Create dev webserver
    * api-mock
    * JSON server (***)
        * allows for full CRUD operations
    * JSON Schema faker (***)
        * specify a schema
        * library creates a set of mock data based on the JSON Schema
        * helps to catch edge cases such as field sizes, pagination, ...
        * will also support insertions and deletes and will write to file
* Full Express (or other) based API

Plan:
1. Declare schema with JSON Schema Faker
1. Generate random data. JSON Schema Faker allows us to use the following to generate random data (bundled with):
    * faker.js
    * chance.js
    * randexp.js
1. Serve data via API
    * JSON Server

## Future goals after this course
* migrate to React 16
* migrate to npm / webpack
* new project - create pricing component with Flexbox and React, feeding from an API