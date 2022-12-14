# React template
## Technologies Used
  - [React](https://reactjs.org/)
  - [TypeScript](https://www.typescriptlang.org/)
  - [Eslit](https://eslint.org/)

## Setup
Project requirements: node v16.13.1, yarn v1.22.19
##### Steps
- create an `.env` file in the application's root directory
- poppulate `.env` file according to `.env.sample`
- run `yarn` in the root of project directory to install all the dependencies
<hr>

## Usage
- Deployment:
  - [setup project](#setup)
  - run `yarn build` to create optimized production build
  - serve `dist` foler
- Development:
    - run `yarn dev` to start app in development mode
- Preview
  - run `yarn preview` to locally check you production build
<hr>

##### Code Examples
```javaScript
// Check whether the app is running in production {boolean}
const isProduction = import.meta.env.PROD;
```
```javaScript
// Ceck whether the app is running in development {boolean} (always the opposite of `import.meta.env.PROD`)
const idDevMode = import.meta.env.DEV;
```
```javaScript
// Using custom environment variables
const someKey = import.meta.env.VITE_SOME_KEY;;
```

## Features that can be added
- Form and Validations:
    - React Hook Form [https://react-hook-form.com]
    - Yup [https://github.com/jquense/yup]
- State management:
  - Redux [https://react-redux.js.org]
  - Redux-Saga [https://redux-saga.js.org]
  - Redux Toolkit [https://redux-toolkit.js.org]