# [Mileum](https://github.com/CodeMileu/mileum)

[![npm version](https://badge.fury.io/js/mileum.svg)](https://badge.fury.io/js/mileum)
[![Build Status](https://travis-ci.org/CodeMileu/mileum.svg?branch=master)](https://travis-ci.org/CodeMileu/mileum)

Intro
=====

Mileum is an Angular 2(v4.3.0) framework intended for **rapid application development**. It's still in **BETA** phase but is published on [npm repository](https://badge.fury.io/js/mileum) and can be installed and used. Documentation is being updated as new features are being released.

Installation
============

First add the package to your `package.json` or install it with the following command from terminal:

`npm install --save mileum`

Then simply import the module into your project and add it to your AppModule's imports with `forRoot()`.

```Typescript
import { MileumModule } from 'mileum/module';

@NgModule({
 ...
 imports: [
  MileumModule.forRoot()
 ]
 ...
})
```

You can now use all the features by simply importing them into desired part of your application, check [usage](#usage) for more info on specific features.

Table of contents
=================

  * [Intro](#intro)
  * [Installation](#installation)
  * [Table of contents](#table-of-contents)
  * [Usage](#usage)
    * [Services](#services)
    * [Components](#components)
  * [Tests](#tests)
  * [Dependencies](#dependencies)

Usage
=====

Services
--------
 
 Currently suppored services:
 - [Radio](https://github.com/CodeMileu/mileum/tree/master/src/services/radio)
 - [RequestManager](https://github.com/CodeMileu/mileum/tree/master/src/services/request-manager)

Components
----------

 Currently supported components:
 - [MileumLogin](https://github.com/CodeMileu/mileum/tree/master/src/components/mileum-login)

Tests
=====

 Tests are not supported yet.

Dependencies
============

 Full list of dependencies:
 - "@angular/common": "^4.0.0"
 - "@angular/compiler": "^4.0.0"
 - "@angular/core": "^4.0.0"
 - "@angular/forms": "^4.0.0"
 - "@angular/http": "^4.0.0"
 - "@angular/platform-browser": "^4.0.0"
 - "@angular/platform-browser-dynamic": "^4.0.0"
 - "@angular/router": "^4.0.0"
 - "core-js": "^2.4.1"
 - "rxjs": "^5.1.0"
 - "ts-helpers": "^1.1.1"
 - "zone.js": "^0.8.4"
