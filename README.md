# E-commerce Back End Starter 
[![Generic badge](https://img.shields.io/badge/License-MIT-yellowgreen.svg)](https://shields.io/)

## Description

This application is a back end for an e-commerce website that uses the latest technologies so that a company can compete with other e-commerce companies.

## License

This application is covered under the MIT License.

## Table of Contents

- [installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Credits](#credits)

## Video

[Video of usage](https://watch.screencastify.com/v/McEPLMCnq4LlBYIXWW7I)

## Screenshots
![RootScreenshot](https://user-images.githubusercontent.com/88356270/142782740-52c2a1f7-d14d-47ad-9cd1-5cede571c813.png)

## Installation

run the following in the terminal:

```md
npm install mysql2
```

```md
npm i sequelize
```

```md
npm install express
```

```md
npm install dotenv
```

## Usage

- create a .env file in the root directory. 
The contents of the file should be:

```md
DB_NAME='ecommerce_db'
DB_USER='root'
DB_PASS='yourpassword'
```
- Insert your mysql user name and password-

- sync sequealize with the application by setting sequelize.sync to true in the server.js file
![Server js screenshot](https://user-images.githubusercontent.com/88356270/142782801-bc4c1703-d5e8-4ee8-9420-2f715fafc3a6.png)

- Then run the following commands in the terminal
```md
npm start
```
- Let everything snyc up and then stop the server by pressing ctrl c in the terminal
- Then change sequealize.sync back to false 
- Then enter the following into the terminal
```md
npm run seed
```
- Once the data is seeded with example data, then everything is good to go. You can then start the server back up
```md
npm start
```
## Credits

Node.js, Sequelize, dotenv, and Express

## Contributing

For contributing to this project, please follow the guidelines of the:

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](https://www.contributor-covenant.org/version/2/1/code_of_conduct/)

## Questions

- [GitHub](https://github.com/beamchristian 'GitHub')
- [Email](mailto:beamchristian@yahoo.com 'Email')
- [Repo](https://github.com/beamchristian/e-commerce-backend-orm 'Repo')
