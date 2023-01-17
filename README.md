# J.A.T.E - Text Editor
  
  [![alt text](https://img.shields.io/static/v1?label=licence&message=MIT%20License&color=GREEN)](https://opensource.org/licenses/MIT)

  ## Description
  The app will be a single-page application that meets the PWA criteria. Additionally, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline.

  ## Table of Contents
  * [User Story](#user-story)
  * [Acceptance Criteria](#acceptance-criteria)
  * [Installation](#installation)
  * [Usage](#usage)
  * [Deployed Link](#deployed-link)
  * [Contributing](#contributing)
  * [Tests](#tests)
  * [License](#license)
  * [Questions](#questions)

  ## User Story
  ```
    AS A developer
    I WANT to create notes or code snippets with or without an internet connection
    SO THAT I can reliably retrieve them for later use
  ```

  ## Acceptance Criteria
  ```
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
  ```

  ## Installation
  `git clone` the repo to your local machine. To use this application, run the following command to install the dependencies:
  <br />
  `npm install`	
  <br />
  Then run the folloring command:	
  <br />`npm run start:dev`

  ## Usage
  Type the following command in your termincal:	
  <br />`npm run start`	
  <br />Then open Insomia and type http://localhost:3000/ to run this application on your local machine.

  ## Deployed Link
  The link to the deployed application is: 

  ## Contributing 
  Fork and then code

  ## Tests
  

  ## License
  <br />[MIT License](https://opensource.org/licenses/MIT)<br />A short and simple permissive license with conditions only requiring preservation of copyright and license notices. Licensed works, modifications, and larger works may be distributed under different terms and without source code. 


  ## Questions
  Github Profile: [faye3091](https://github.com/faye3091)
  <br />
  Reach me with additional questions at faye_3091@yahoo.com
  