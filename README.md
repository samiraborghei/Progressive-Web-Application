# Progressive-Web-Application

## Description

The deployed application is a browser-based web text editor that enables users to create notes and write code, regardless of whether they have an internet connection. It is designed as a single-page application with various data persistence techniques to ensure redundancy. This means that even when offline, users can still access previously visited pages. The application has been deployed to Heroku, and you can access it using the provided URL.
Heroku: https://p-web-app-abf671db8d65.herokuapp.com
 
https:
Repo: git@github.com:samiraborghei/Progressive-Web-Application.git


# User Story
As a developer, my goal is to create a web application that allows users to create and store notes or code snippets, providing the flexibility to do so with or without an internet connection. This ensures that users can conveniently retrieve their saved content whenever they need it, regardless of their online status.

# Acceptance Criteria
``````
    GIVEN a text editor web application
    WHEN I open my application in my editor
    THEN I should see a client server folder structure
    WHEN I run `npm run start` from the root directory
    THEN I find that my application should start up the backend and serve the client
    WHEN I run the text editor application from my terminal
    THEN I find that my JavaScript files have been bundled using webpack
    WHEN I run my webpack plugins
    THEN I find that I have a generated HTML file, service worker, and a manifest file
    WHEN I use next-gen JavaScript in my application
    THEN I find that the text editor still functions in the browser without errors
    WHEN I open the text editor
    THEN I find that IndexedDB has immediately created a database storage
    WHEN I enter content and subsequently click off of the DOM window
    THEN I find that the content in the text editor has been saved with IndexedDB
    WHEN I reopen the text editor after closing it
    THEN I find that the content in the text editor has been retrieved from our IndexedDB
    WHEN I click on the Install button
    THEN I download my web application as an icon on my desktop
    WHEN I load my web application
    THEN I should have a registered service worker using workbox
    WHEN I register a service worker
    THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
    WHEN I deploy to Heroku
    THEN I should have proper build scripts for a webpack application
``````

## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [References](#references)
* [License](#license)

## Installation

* To build this text editor, it is necessary to implement multiple methods and establish a connection to an IndexedDB database. The objective is to enable the text editor to store data in the IndexedDB database effectively. This entails developing the required functionality for seamless integration and data storage within the application.

* This application will require the installation of Node.js and various npm packages.

*   The Node Package Manager (npm) serves as a software manager and installer for Node.js projects. It facilitates the placement of modules, allowing the project to utilize them efficiently. Additionally, npm intelligently handles dependency conflicts. The initialization process is carried out using the command **npm init**, which generates a package.json file. This file contains all the application details that the user inputs during the npm initialization process. 

*  This application will use the following npm packages:-

         * npm install express (express.js)
         * npm install --save-dev webpack (Webpack)
         * npm install webpack-dev-server --save-dev (webpack-dev-server)
         * npm install --save-dev webpack-pwa-manifest (WebpackPwaManifest)
         * npm install babel (Babel)
         * npm install --save-dev css-loader (CSS-loader)
         * npm install concurrently --save (run multiple commands concurrently.) (Concurrently)
         * npm npm install idb (IndexedDB)

* The required modules are bundled in the package.json file and at CLI or integrated terminal type in **npm run install**, the modules will be installed.       

## Usage

1.
``````    
GIVEN a text editor web application, 
WHEN I open my application in my editor
THEN I should see a client server folder structure
``````
*Below is the screenshot of the client server folder structure.  The folder structure have been set up or given in this structure.*

![alt text](<img width="680" alt="Screen Shot 2023-06-27 at 1 25 45 PM" src="https://github.com/samiraborghei/Progressive-Web-Application/assets/124013032/d87a293a-b127-4653-8438-42582547793f">)



2.
``````
    WHEN I run `npm run start` from the root directory
    THEN I find that my application should start up the backend and serve the client
    WHEN I run the text editor application from my terminal
    THEN I find that my JavaScript files have been bundled using webpack
    WHEN I run my webpack plugins
    THEN I find that I have a generated HTML file, service worker, and a manifest file
``````
*Below is the screenshot of the running at npm run start and npm run build* 

![alt text](/assets/images/TE02.png)

*Below is the screenshot of the generated HTML, service worker and a manifest file*

![alt text](/assets/images/TE08.png)

3.
``````
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
``````
*Below is the screenshot of the text editor "Just Another Text Editor (J.A.T.E)"*

![alt text](/assets/images/TE03.png)

4.
``````
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
``````
*Below is the  screenshot of content in the text editor has been retrieved from the IndexedDB"*

![alt text](/assets/images/TE05.png)

5.
``````
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
``````
*Below is the screenshot of icon on the desktop"*

![alt text](/assets/images/TE04.png)

6.
``````
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
``````
*Below is the screenshot of the static assets pre cached upon loading with subsequent pages and static assets"*

![alt text](/assets/images/TE09.png)

![alt text](/assets/images/TE10.png)

7.

 ````````
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application 
````````
![alt text](/assets/images/TE11.png)


## References

*   https://web.dev/progressive-web-apps/
*   Mini project
*   Heroku Deployment Guide
 
## License

This project is licensed under the terms of the MIT license.
