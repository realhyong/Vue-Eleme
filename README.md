# COVID-19 promotion website

[简体中文](README_CN.md)<br/>
English(Current)

## Introduction
This repository contains all the code and files needed to reproduce the Elemo page. Suitable for vue beginners, exploring component layouts and calls for front-end learner.

**Note**: This site was created by me through a GitHub open source project and third party video learning. Please understand!

## Content

- `build/` : holds the settings for Webpack development and packaging, including entry files, output files, modules used, etc.
- `config/` : specifies the static resource paths for development and packaging, the file types to be compressed, and the port numbers to be used for development.
- `src/` : The main folder for operations, all components, App.vue are operated in this folder.
- `static/` : A folder for static resources, resources that will not change, including data, images, etc.
- `index.html` : The entry file for the vue project, usually introduced into App.vue.

===
- `.baberlrc` : The configuration file for Babel(configuration file).
- `.editorconfig` : Ensures that the project code is formatted consistently (configuration file).
- `.eslintignore` : Causes ESLint to ignore specific files and directories (configuration file).
- `.eslintrc.js` : Configures ESLint (configuration file).

## Usage
> Install the dependencies for the project
> $ npm install
> 
> Open the project at localhost:8088
> $ npm run dev
<br/>

## Studying
1. understand the layout composition of Vue and the basics of writing components
2. be familiar with and use `Axios` to make HTTP requests and use the data returned
3. use `Vuex` to communicate with data so that public data or data between different components can be processed
4. use `Vue-Router` to create single-page applications that can update content without refreshing the page
5. learn how to do `Communication between components`.
6. learn how to create and maintain a complete Vue project