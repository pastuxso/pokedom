# PokeDOM

[![Build Status](https://travis-ci.org/pastuxso/pokedom.svg?branch=master)](https://travis-ci.org/pastuxso/pokedom)

Simple application to monitoring websites only for educational purpose.

## Features

- Manage multiple domains and paths.
- Support for GET/POST/DELETE/PATCH.
- Notifications via Email, Telegram and Slack.
- Realtime dashboard.
- Metrics powered by InfluxDB.
- Only request, no rendering content.

## Setup

### Requirements

  - InfluxDB

### Development

  - Copy sample of environment variables `cp .env.sample .env`
  - Running development server `node server.js`
  - Running tests `npm tests`
  - Running eslint `npm run lint`
  - Running tests watching file changes `npm run watch-test`
