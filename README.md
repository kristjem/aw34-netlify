## Netlify & FaaS Overview

**Netlify** is a platform for deploying web apps and serverless functions.  
**FaaS (Function as a Service)** lets you run backend code as isolated functions, triggered by HTTP requests.

## About This App

This school lesson app demonstrates FaaS on Netlify using a simple guitar inventory API.  
The main logic is in `/functions/guitars.js`, allowing you to GET, POST, and DELETE guitars via REST endpoints.

## How to Use

- Deploy the app on Netlify or run locally with `npm start`.
- Use the REST endpoints to manage guitars.

## Bruno REST Collection

A Bruno REST collection is provided in `/bruno` with two environments:
- **local dev** (for local testing)
- **netlify prod** (for production)

Use Bruno to easily try out and test the API.