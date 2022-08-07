# J2F Frontend

This is the React front-end for [J2F](yummy-ink.surge.sh).

## Motivation
<!-- A short description of the motivation behind the creation and maintenance of the project. This should explain **why** the project exists. -->

Wanting to learn more about React and to build a bigger application, I built 
the front end portion for the back end application that I designed in Express.

[(Backend Application)](https://github.com/JuanLee10/j2f-be). 

<!-- ## Build status
Build status of continus integration i.e. travis, appveyor etc. Ex. - 

[![Build Status](https://travis-ci.org/akashnimare/foco.svg?branch=master)](https://travis-ci.org/akashnimare/foco)
[![Windows Build Status](https://ci.appveyor.com/api/projects/status/github/akashnimare/foco?branch=master&svg=true)](https://ci.appveyor.com/project/akashnimare/foco/branch/master)

## Code style
If you're using any code style like xo, standard etc. That will help others while contributing to your project. Ex. -

[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](https://github.com/feross/standard)
 
## Screenshots
Include logo/demo screenshot etc. -->

## Tech/framework used

### Built with
<b>Frontend:</b>
- [React](https://reactjs.org/)
- [React Router](https://reactrouter.com/web/guides/quick-start)
- [Lodash](https://lodash.com/)
- [Node Sass](https://github.com/sass/node-sass)
- [JSON Web Token](https://github.com/auth0/node-jsonwebtoken)
- [Axios](https://github.com/axios/axios)

## Features
The application allows users to sign up and log into their accounts to 
view the descriptions and jobs that are available for different companies. 
The user can apply for various jobs which makes an AJAX request to our 
API and makes the corresponding change in the front-end. Various routes 
to the application are protected through a middleware ensuring that only 
loged in user can view those pages. 

## How to use?
In order to host the project locally, follow these steps

    git clone https://github.com/JuanLee10/j2f-fe.git
    cd j2f-fe
    npm install
    npm start
    
In a new terminal tab (cmd + t) for the backend
    
    cd ..
    git clone https://github.com/JuanLee10/j2f-be.git
    cd j2f-be
    npm install
    psql < j2f.sql
    npm start



## Future directions


<!-- 

## Code Example
Show what the library does as concisely as possible, developers should be able to figure out **how** your project solves their problem by looking at the code example. Make sure the API you are showing off is obvious, and that your code is short and concise.

## Installation
Provide step by step series of examples and explanations about how to get a development env running.

## API Reference

Depending on the size of the project, if it is small and simple enough the reference docs can be added to the README. For medium size to larger projects it is important to at least provide a link to where the API reference docs live.

## Tests
Describe and show how to run the tests with code examples.

## Contribute

Let people know how they can contribute into your project. A [contributing guideline](https://github.com/zulip/zulip-electron/blob/master/CONTRIBUTING.md) will be a big plus.

## Credits
Give proper credits. This could be a link to any repo which inspired you to build this project, any blogposts or links to people who contrbuted in this project. 

#### Anything else that seems useful

## License
A short snippet describing the license (MIT, Apache etc)

MIT © [Yourname]() -->