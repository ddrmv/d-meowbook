# Project Acebook (aka Meowbook)

A two-week social media website team project at Makers.

To practice JS, Node and working in a team with agile and scrum practices, pair programming, problem solving, test-driving, github workflow.

Build onto a basic database and web app setup. Additional functionality has been added by the team, complete with design, implementation and full test coverage.

Deployed on Heroku and later retired.

### Features:

- Sign-up, log-in, log-out
- Post text and images
- Comment on posts
- Like posts
- See user profiles
- Make, accept, decline friend requests

# Tools

![JavaScript Badge](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000&style=flat)
![HTML5 Badge](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=fff&style=flat)
![CSS3 Badge](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=fff&style=flat)
 . ![npm Badge](https://img.shields.io/badge/npm-CB3837?logo=npm&logoColor=fff&style=flat)
![Node.js Badge](https://img.shields.io/badge/Node.js-393?logo=nodedotjs&logoColor=fff&style=flat)
![Express Badge](https://img.shields.io/badge/Express-000?logo=express&logoColor=fff&style=flat)
![Handlebars.js Badge](https://img.shields.io/badge/Handlebars.js-f0772b?style=flat&logo=handlebarsdotjs&logoColor=black)
![Bootstrap Badge](https://img.shields.io/badge/Bootstrap-7952B3?logo=bootstrap&logoColor=fff&style=flat)
![MongoDB Badge](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=fff&style=flat)
 . ![Jest Badge](https://img.shields.io/badge/Jest-C21325?logo=jest&logoColor=fff&style=flat)
![Cypress Badge](https://img.shields.io/badge/Cypress-17202C?logo=cypress&logoColor=fff&style=flat)
 . ![Heroku Badge](https://img.shields.io/badge/Heroku-430098?logo=heroku&logoColor=fff&style=flat)


# Team

[Rita Aktay](https://github.com/ritaaktay) | [D. Dramchev](https://github.com/ddrmv) | [Marina Ivanova](MarinaIvanova-1) | [Jovi Lau-Kwong](https://github.com/44jovi) | [Yichao Qian](https://github.com/oahciy) | [Gregory Redos](https://github.com/g-redos)

# Installation

### With NPM and Node.js installed

1. Clone this repository
2. Install Node.js dependencies
   ```
   npm install
   ```
3. Install an ESLint plugin for your editor. For example: [linter-eslint](https://github.com/AtomLinter/linter-eslint) for Atom.
4. Install [MongoDB@5](https://www.mongodb.com/docs/v5.0/administration/install-community/)

5. Start MongoDB
   ```
   sudo systemctl start mongod
   ```

### Start

```
npm start
```
Start the server and browse to [http://localhost:3000](http://localhost:3000).


### Start test server

The server must be running locally with test configuration for the
integration tests to pass.

```
npm run start:test
```

This starts the server on port `3030` and uses the `acebook_test` MongoDB database,
so that integration tests do not interact with the development server.

### Test

To run all tests:
```
npm test
```
To run a check:
```bash
npm run lint              # linter only
npm run test:unit         # unit tests only
npm run test:integration  # integration tests only
```

# Development, testing, deployment

### Design with Excalidraw

![Excalidraw chart](/public/images/diagram.png)

### Project management with Trello

![Excalidraw chart](https://i.imgur.com/UTLqqMw.png)

### Test coverage with Jest

![Tests pass](/public/images/tests.png)

### Deployment on Heroku

![Working app](https://i.imgur.com/h6RnOlT.png)
