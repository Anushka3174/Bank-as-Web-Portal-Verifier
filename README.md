# Bank's Portal powered by Affinidi API

This is a react application that has a basic UI with some of the functionalities that Affinidi offers. You can use this app to play around with some of the functionalities offered in the Affinidi API and eventually enable SSI for your own application(s).

## Installation

`npm install`

Install using npm instead of yarn because the current package-lock.json was
generated using npm.

## Environment

API KEY HASH is required to use this application. You can get the API key [here](https://apikey.affinidi.com/).

Using the API KEY HASH:
- Option 1: create an `.env` file by `cp .env.example .env` and replacing the value in the `<<>>`

- Option 2: Add the API KEY HASH created above to your package.json into the `start` and `build` commands like this:

```
......
  "scripts": {
    "start": "REACT_APP_ENVIRONMENT=prod REACT_APP_API_KEY_HASH=........ react-scripts start",
    "build": "REACT_APP_ENVIRONMENT=prod REACT_APP_API_KEY_HASH=........ react-scripts build",
......
```

## Quick intro

You can visit `/intro` route to see a quick explanation and overview of an SSI cycle.

# Below was generated by [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
