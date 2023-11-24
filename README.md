# plugin-account

[![NPM Downloads](https://img.shields.io/npm/dt/plugin-{your-plugin-name})](https://www.npmjs.com/package/plugin-{your-plugin-name})

The Account Plugin includes a Signup endpoint + Password-Forget & Logout with CSRF protection

## Purpose

The purpose of a signup flow and features such as password forget is the ease of building multi-tenant web applications with interactive features. This shall be just the start.

## Configuration

Noone required 

## Scripts

### `build`

Running `npm run build` will bundle your plugin with Webpack for production.

### `dev`

Running `npm run dev` will watch your plugin's source code and automatically bundle it with every change.

## Usage

`POST /signup {firstName: string, lastName: string, username: string, password: string}`
`GET /password-forget {username: string}`
`GET /logout {...header: token: token / _csrf_token=... }`


