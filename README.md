This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Getting Started

### Setup
1) Navigate to the `/web_app` directory. 
2) Install the required npm packages.
```javascript
  npm install
```
3) Navigate to the `/web_app/client` directory.
4) Repeat the npm package installation.
```javascript
  npm install
```
5) You must have the following environment variables set to valid credentials:
  - ```MONGO_USERNAME```
  - ```MONGO_PASSWORD```

## Usage
To run Purple News:
1) Navigate to the `/web_app` directory. 
2) Input the following command to start the server and launch a client on local host port 3000.
```javascript
npm run dev
```
## Available Scripts

In the project directory, you can run:

### `npm start`

Starts the server.

### `npm run server`

Starts the server using nodemon (preferred).

### `npm run client`

Starts the `react` client. This will trigger the React start script.

### `npm run dev`

For development, this starts the server and client concurrently.
