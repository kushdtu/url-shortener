# URL Shortener Demo

A URL Shortener Application built with Node.js, Express and MongoDB.

This project is live at https://tiny-urlshort.herokuapp.com/

## Prerequisites

You must have Node.js, npm and MongoDB installed on your machine. This project was built against the following versions:

- Node v13.13.0
- npm v6.14.4
- MongoDB v4.2.6

## Setup

- Clone this repo to your machine
- `cd` into the project folder and run `npm install`
- make `.env` file and put `DATABASE=mongodb://localhost:27017`
- Run `npm start`
- Navigate to http://localhost:4100

## How to use

- Enter a URL into the input field and hit **Shorten**. The shortened URL will be displayed on the page.
- Open the shortened URL in a new tab. It should redirect you to the original URL.