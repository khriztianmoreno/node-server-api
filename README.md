# Node.JS - API Example
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

Hello, and welcome! This Node.JS sample application that demonstrates an architecture for building a complete production API with Node.JS, Express.JS.

- Built with Node.js and Express

## Express Router and Routes

| Route           | HTTP Verb | Route Middleware   | Description                          |
| --------------- | --------- | ------------------ | ------------------------------------ |
| /api/users      | GET       |                    | Get list of users                    |
| /api/users      | POST      |                    | Creates a new user                   |
| /api/users/:id  | GET       |                    | Get a single user                    |
| /api/users/:id  | DELETE    |                    | Deletes a user, restriction: 'admin' |
