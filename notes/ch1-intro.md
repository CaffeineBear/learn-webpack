# Introduction

## Why webpack?
In classic javascript project, the project was depending on the order of loading 
files. And this was not good for the large project which has a lot of javascript
files. 

Due to this problem, they tried to use `Grunt` and `Gulp` to pack assets and javascript
files into one file. However, this was still not enough to solve dependency issues. 

To solve the dependency issues, they used to be `Require.js`. However, this was not 
powerful as the webpack that we use today. 

## What is webpack?
Webpack is a static module bundler for modern javascript applications. It will recursively
builds a dependency graph while processing your application. And it will package modules 
into one or moure bundles. 

Now there are no hidden dependencies and order does not matter as the webpack handles that
for you. 