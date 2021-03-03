# Simple Client Server

A simple `client` to `server` communication POC used for `web-dev` basics introduction (part 1 & 2) for talk in `TechieWeek` at `UTFL`.

# Client (Frontend)

This is a very simple stripped down version of a client restricted to `cli` mode.

- Can make `HTTP` requests.
- Connect to a `backend` using a `websocket`.
- Can process and display `JSON` data received backend.

from `minimal-client` folder.

```
$ npm install
$ node client.js
```

# Backend (Backend App)

This is a simple `Nodejs-Express` app encapsulating a simple `API` for `create`, `read`, `update` & `delete`.

- Can handle `API` requests. `(Restful API)`.
- Can handle `socket` communication.
- Performs `CRUD` operations on a database `(backed by a data source)`.
- Demonstrate the use of `Docker` containers to deploy backend app.

from `minimal-backend` folder. This runs the `nodemon` backed `backend` app.

```
$ npm install
$ npm start
```

# More to Cover.

- Refactor to seperate `backend` & `frontend` git repositories like all my other POCs.
- Add more use cases and features that come in from `user-stories`.
- Deploy the `minimal-backend` on `AWS` & use `S3` for storing/retriving assets.
- Convert `minimal-client` to a functional `web-app` (frontend app) using `React` or `Angular` instead of `cli` mode.
