# generator-ui5g 

This is a basic generator for sapui5/openui5, use gulp to build

## Installation

First, install [Yeoman](http://yeoman.io) and generator-ui5g using [npm](https://www.npmjs.com/) (we assume you have pre-installed [node.js](https://nodejs.org/)).

```bash
npm install -g yo
npm install -g generator-ui5g
# or
yarn global add yo
yarn global add generator-ui5g
```

## Generate Project

Then generate your new project:

**PLEASE MAKE YOUR PROJECT DIRECTORY MANUALLY**

```bash
# yes you have to mk your project directory manually
mkdir sample-project
cd sample-project
yo ui5g
# it will ask your 3 questions
? App name theo1
? App namespace corp.sap.msms.theo
? SAPUI5 or OpenUI5? OpenUI5
# please make sure your answer is logical, because generator not process empty or wrong input error
```

**PLEASE CHOOSE OpenUI5 IF YOU DONT HAVE SAPUI5 LINCENSE**

and install dependencies

```bash
yarn
# or
npm i
```

## Dev

This template is based on [UI5 Workthrough](https://sapui5.hana.ondemand.com/test-resources/sap/m/demokit/tutorial/walkthrough/37/webapp/test/mockServer.html?sap-ui-theme=sap_belize), It contains most features of ui5, if you not need that, delete them directly

start your project

```bash
yarn run dev
# or
npm run dev
```

you can use ```es6/es2015``` features and ```less``` in project, and js sourcemap is open defaultly

you can edit ```proxies.js``` to add more proxy srevices

also, ```eslintrc``` is exist in project directory


## About

This generator is written by theo but some ideas come from Madeleine, and it only can generate really simple project. Very pleased to be able to help you.