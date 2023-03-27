# ch19_baxley_text_editor

## Table of Contents:

- [Description](#description)
- [Acceptance Criteria](#acceptance-criteria)
- [Installation](#installation)
- [Usage](#usage)
- [Contribution](#contribution)
- [Testing](#testing)
- [Credits](#credits)
- [License](#license)

## Description

This project was the creation of application that simulates the back end of a Ecommerce website. The application utilizes MySQL2 created databases through Sequelize interactions. The application allows for a user to view, create, update, and delete products, categories, and tags related to sales items on the Ecommerce website. The application can not be seen on a static webpage so a walkthrough video has been created to show functionality. (Video Link)

## Acceptance Criteria

GIVEN a text editor web application<br>
WHEN I open my application in my editor<br>
THEN I should see a client server folder structure<br>
WHEN I run `npm run start` from the root directory<br>
THEN I find that my application should start up the backend and serve the client<br>
WHEN I run the text editor application from my terminal<br>
THEN I find that my JavaScript files have been bundled using webpack<br>
WHEN I run my webpack plugins<br>
THEN I find that I have a generated HTML file, service worker, and a manifest file<br>
WHEN I use next-gen JavaScript in my application<br>
THEN I find that the text editor still functions in the browser without errors<br>
WHEN I open the text editor<br>
THEN I find that IndexedDB has immediately created a database storage<br>
WHEN I enter content and subsequently click off of the DOM window<br>
THEN I find that the content in the text editor has been saved with IndexedDB<br>
WHEN I reopen the text editor after closing it<br>
THEN I find that the content in the text editor has been retrieved from our IndexedDB<br>
WHEN I click on the Install button<br>
THEN I download my web application as an icon on my desktop<br>
WHEN I load my web application<br>
THEN I should have a registered service worker using workbox<br>
WHEN I register a service worker<br>
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets<br>
WHEN I deploy to Heroku<br>
THEN I should have proper build scripts for a webpack application<br>

## Installation

A user will need to instal the package.json modules in order to run this application. The user may do this by simply running "npm i" in the terminal. This will install all modules as well as the webpack.config documents.

## Usage

The user will access the application via Heroku. The user will simply need to follow the below link to access the application. the user will then follow the prompts to access the text editor application.

## Contribution

N/A

## Testing

No testing was utilized for this project

## Credits

### Team Members:

- James Baxley | Github: [Kaneknah](https://github.com/Kaneknah)

### Technologies utilized:

- webpackManifest
- Express.js
- Sequelize
- Node.js
- IndexedDB
- babel-loader
- css-loader
- style-loader

### GitHub Link: <https://github.com/Kaneknah/ch13_orm_commerce_backend_app>

## License

Apache License 2.0
...
