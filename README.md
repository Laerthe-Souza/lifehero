<h1 align="center">
<br>
  <img src='https://svgshare.com/i/TML.svg' title='Life Hero' width="120" />
<br>
<br>
Life Hero
</h1>

<p align="center">A clone of the BeTheHero application, developed by @Rocketseat in the 11th Omnistack Week</p>

<p align="center">
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License MIT">
  </a>
</p>

<hr />

## View the web app

<div align="center">
  <img src="https://i.ibb.co/fGqKYh1/sign-in.png" alt="Sign in page" width="600" height="350" />

  <p>
    This page is responsible for receiving the user's email and password and subsequently authenticating with the database. Then, a 'token' is provided to validate all future operations (requests) made in the API.
  </p>
</div>

<hr />

<div align="center">
  <img src="https://i.ibb.co/XxFXZJT/sign-up.png" alt="Sign up page" width="600" height="350" />

  <p>  
    This page is responsible for receiving user data, validating all fields and then creating a new record in the database. After registering, the user must wait 24 hours for the administrator to verify the veracity of the data and activate the registration.
  </p>
</div>

<hr />

<div align="center">
  <img src="https://i.ibb.co/xzsc8g8/dashboard.png" alt="Dashboard page" width="600" height="350" />

  <p>  
    This page is the dashboard, where the ONG views all incidents and performs operations.
  </p>
</div>

<hr />

<div align="center">
  <img src="https://i.ibb.co/F5hpqMJ/new-incident.png" alt="New incident page" width="600" height="350" />

  <p>    
  This page is where the ONG registers a new incident.
  </p>
</div>

<hr />

<div align="center">
  <img src="https://i.ibb.co/7XCtXMw/Life-Hero.png" alt="Profile page" width="600" height="600" />

  <p>    
    This page is where the ONG can updating your datas and uploading profile picture.
  </p>
</div>

<hr />

## View the mobile app

<div align="center">
  <img src="https://i.ibb.co/ckDkPW7/Screenshot-20210125-013601-1.png" alt="Splash screen" width="250" height="500" />
  <img src="https://i.ibb.co/N6hvzQk/Screenshot-20210125-013621-1.png" alt="Dashboard screen" width="250" height="500" />
  <img src="https://i.ibb.co/cgF7sL0/Screenshot-20210125-013634-1.png" alt="Favorites incidents screen" width="250" height="500" />
  <img src="https://i.ibb.co/qBVdYwc/Screenshot-20210125-013650-1.png" alt="Details incidents screen" width="250" height="500" />
  <img src="https://i.ibb.co/R6CHNHm/Screenshot-20210125-013656-2.png" alt="Details incidents screen" width="250" height="500" />
</div>

## Getting started

1. Clone this repo using `git clone git@github.com:laerthe-souza/lifehero.git`
2. Move yourself to the appropriate directory: `cd lifehero`<br />
3. Run `yarn` to install dependencies<br />
4. Run `yarn lerna bootstrap` to install the packages dependecies

### Getting started with the server

1. Move yourself to the backend folder: `cd server`
2. Create a `.env` file and add all the environment variables required
3. Run `yarn dev` to start the server

### Getting started with the web app

1. Move yourself to the frontend folder: `cd web`
2. Create a `.env` file and add all the environment variables required
2. Run `yarn start` to start the web application

### Getting started with the mobile app

1. Move yourself to the mobile folder: `cd mobile`
2. Run `yarn start` or `expo start` to start the mobile app

## License

This project is licensed under the MIT License - see the [LICENSE](https://opensource.org/licenses/MIT) page for details.
