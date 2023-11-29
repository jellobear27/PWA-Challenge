# Title.
J.A.T.E - Just Another Text Editor

# Description.
J.A.T.E (Just Another Text Editor) is a progressive web application that serves as a simple yet powerful browser-based text editor. It operates as a single-page application and meets the criteria of a Progressive Web App (PWA). The editor provides the ability to create notes or code snippets, both online and offline, ensuring reliable access to your content.

## Table of Contents
- [Overview](#Overview)
- [User Story](#User-Story)
- [Acceptance Criteria](#Acceptance-Criteria)
- [Features](#Features)
- [Getting Started](#Getting-Started)
- [Usage](#Usage)
- [Technologies Used](#Technologies-Used)
- [ScreenShots](#screenshots)
- [Deployment](#Deployment)
- [Contributing](#Contributing)
- [License](#License)
- [Contact](#Contact)

## Overview
This project is designed to be a text editor accessible in a web browser. It utilizes IndexedDB for data storage, ensuring content persistence even without an internet connection. It employs the idb package, a lightweight wrapper around the IndexedDB API, to facilitate efficient data storage and retrieval.

## User Story
As a developer, I want to create notes or code snippets with or without an internet connection so that I can reliably retrieve them for later use.

## Acceptance Criteria
- Upon opening the application, a client-server folder structure is visible.
- Running npm run start from the root directory initiates the backend and serves the client.
- JavaScript files are bundled using webpack.
- Webpack plugins generate HTML, service worker, and manifest files.
- The text editor functions seamlessly in the browser, supporting next-gen JavaScript.
- IndexedDB immediately creates a database storage upon opening the text editor.
- Content entered in the text editor and clicked off the DOM window is saved in IndexedDB.
- Reopening the text editor retrieves the saved content from IndexedDB.
- Clicking the "Install" button allows downloading the web application as an icon on the desktop.
- The web application has a registered service worker using workbox.
- Static assets are precached on loading, along with subsequent pages and static assets.
- Proper build scripts for a webpack application are in place for deployment.
Features
- IndexedDB integration for data storage and retrieval.
- Support for offline content access and editing.
- Progressive Web App (PWA) characteristics.
- Next-gen JavaScript usage without compromising functionality.
- Service worker registration and asset caching for offline access.

## Getting Started
- Clone the repository:

- bash
- Copy code
- git clone 
https://github.com/jellobear27/PWA-Challenge
- Install dependencies:

- bash
- Copy code
- npm install

## Usage
- Start the application:

- bash
- Copy code
- npm run start
- Access the text editor via the provided URL in your browser.

## Technologies Used
- JavaScript
- HTML/CSS
- IndexedDB
- Webpack
- Workbox
- Express
- Babel

## ScreenShots
[![Alt Text](assets/images/Screenshot%202023-11-28%20at%209.08.40%20PM.png)]
[![Alt Text](assets/images/Screenshot%202023-11-29%20at%203.02.45%20PM.png)]


## Deployment
View deployed application with Heroku at:

https://pwa-challenge-js-eae69d7576c3.herokuapp.com/

## Contributing
Contributions are welcome! Please fork the repository and create a pull request for any suggested enhancements or bug fixes.

## License:MIT https://opensource.org/license/mit/
Copyright <2023> <COPYRIGHT Janell Smith>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Contact
For any inquiries or suggestions, feel free to contact me via GitHub: 
https://github.com/jellobear27

