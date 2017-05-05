# CoreDataStore

[![This image on DockerHub](https://img.shields.io/docker/pulls/stuartshay/coredatastore.svg)](https://hub.docker.com/r/stuartshay/coredatastore/) [![Build status](https://ci.appveyor.com/api/projects/status/4j2ebt69uw0e0wmg/branch/master?svg=true)](https://ci.appveyor.com/project/StuartShay/coredatastore/branch/master)
[![CircleCI](https://circleci.com/gh/stuartshay/CoreDataStore.svg?style=shield)](https://circleci.com/gh/stuartshay/CoreDataStore)
[![Build Status](https://travis-ci.org/AngularVN/CoreDataStore.Web.svg?branch=master)](https://travis-ci.org/AngularVN/CoreDataStore.Web)
[![dependencies Status](https://david-dm.org/AngularVN/CoreDataStore.Web/status.svg)](https://david-dm.org/AngularVN/CoreDataStore.Web)
[![devDependencies Status](https://david-dm.org/AngularVN/CoreDataStore.Web/dev-status.svg)](https://david-dm.org/AngularVN/CoreDataStore.Web?type=dev)
[![Code Climate](https://codeclimate.com/github/AngularVN/CoreDataStore.Web/badges/gpa.svg)](https://codeclimate.com/github/AngularVN/CoreDataStore.Web)


Angular2 with TypeScript and Gulp
=================================

A basic Angular2 application with Gulp as build system.

Prerequisites
-------------

- nodejs
- gulp and gulp-cli
- typings
- typescript
- ts-node

Running
-------

Install dependencies:

> cd src/CoreDataStore.Web
> npm install

`node_modules` and `typings` directories should be created during the install.

Environment Linux/Unix
```bash
export NG_ENVIRONMENT=Dev
export LANDMARK=http://informationcart.eastus2.cloudapp.azure.com:80/api/
export ATTRACTION=http://informationcart.eastus2.cloudapp.azure.com:83/api/
export MAPSAPI=http://informationcart.eastus2.cloudapp.azure.com:82/api/
export REPORTSAPI=http://informationcart.eastus2.cloudapp.azure.com:84/api/
```

Environment Windows
```bash
set NG_ENVIRONMENT=Dev
set LANDMARK=http://informationcart.eastus2.cloudapp.azure.com:80/api/
set ATTRACTION=http://informationcart.eastus2.cloudapp.azure.com:83/api/
set MAPSAPI=http://informationcart.eastus2.cloudapp.azure.com:82/api/
set REPORTSAPI=http://informationcart.eastus2.cloudapp.azure.com:84/api/
```

Build the project:

```bash
npm run clean
npm run build
```

`build` directory should be created during the build

> npm start

The application should be displayed in the browser.

> dotnet run
Start webservice with dotnet
