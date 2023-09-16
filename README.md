# Uni-One Dashboard

// TODO: Project description here

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn lint`

Runs eslint on all Javascript/Typescript files.

### `yarn run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

## Git Hooks

### pre-commit hooks

- ESLint

### commit-msg hooks

- commitlint: Following conventional commit. Check out [here](https://www.conventionalcommits.org/en/v1.0.0/)

### pre-push hooks

- `yarn test`: Having a threshold of 85% for statements, branches, functions and lines