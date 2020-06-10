# Project Overnight: Reviews Service

The reviews module of Project Overnight dynamically renders visitor reviews and represents rating averages via bar graphs.

![Reviews Demo](demo/demo.gif)
*The outside margins of this module were left unset, so that they can be controlled on the proxy level.*

## Related Projects

  - Photo Banner Module: https://github.com/project-overnight/po-photo-banner
  - Description Module: https://github.com/project-overnight/po-description
  - Reservation Module: https://github.com/project-overnight/po-reservations

## Usage

**Install dependencies**
> npm install

**Set up environment variables**
- Make a copy of .env_sample and configure the environment variables as necessary.
- Save as .env and ensure it is added to .gitignore.

**Seed the database**
> npm run seed

**Build webpack bundle**
> npm run build

**Start up the server**
> npm start

## Style Guide
This module follows [Airbnb style guide](https://github.com/airbnb/javascript)