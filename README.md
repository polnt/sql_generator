# sql_generator

Simple SQL Generator using package openapi-generator from OpenAPITools (https://github.com/OpenAPITools/openapi-generator/tree/master)

Prerequisites:
 - Nodejs
 - Java

Try it:
 - Run `yarn && yarn generate` or `npm i && npm run generate` will generate a SQL file from input/dummy.yml

Installation:
 - Run `yarn` or `npm i`

Usage:
 - First, replace dummy.yml by your own OAS YAML file into input/ directory
 - Then run `yarn generate` or `npm run generate`, and that's all ! Your SQL file is waiting for you in output/ directory

If you wish to generate an other file:
 - Run `yarn reset` or `npm run reset` to clean output/ directory
 - Run `yarn reset:hard` or `npm run reset:hard` to clean both input/ and output/ directories