# Webpacker + Docker

A minimal example app for showing how Webpacker can be integrated with Docker and Docker Compose.

This demonstrates how the asset pipeline and webpacker can co-exist. I have however included app/javascript/src/application.css in the webpack manifest so you can see the benefits of live code reloading with webpack.

## Setup

Install [Docker](https://docs.docker.com/install/) and [Docker Compose](https://docs.docker.com/compose/install/).

Run `docker-compose up --build`

For bonus points, try changing the colour of the H1 in app/javascript/src/application.css. Look ma, no refresh!

## Now you know

You can run `docker attach webpackerdocker_web_1` in a new terminal tab if you want a native-like byebug/pry experience.
