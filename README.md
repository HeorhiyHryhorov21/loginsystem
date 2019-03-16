# PHP Login/Signup System

# Getting started

To get the Node server running locally:

- Clone this repository
- `npm install` to install all required dependencies
- `node app.js` to start the local server

Technologies used:
------------------
##### Prerequisites

- `PHP` *_required_*
	- Minimum version: `7.0`
	- `pdo_mysql` extension required
	- Recommended to enable `shell_exec`

- `MySQL` *_required_*
	- Version `5.6+` recommended


## Application Structure

- `app.js` - The entry point to the application. This file defines our express server. It also requires the routes and models we'll be using in the application.
- `assets/` - This folder contains static js and css files.
- `controllers/` - This folder contains controllers for the application.
