# App Name

## Summary

- [App information](#app-information)
- [Installation](#installation)
- [Local run](#local-run)
- [Tests](#tests)
- [Build](#build)
- [Deploy](#deploy)
- [Best practices](#best-practices)
- [Naming convention](#naming-convention)
  - [File naming](#files-naming)
  - [Variables and classes naming](#variables-and-classes-naming)
- [Resources](#resources)
- [Learn More](#learn-more)

## App information

- App name :
- Description :
- App repositories :
  - [Front-end]()
  - [Back-end]()

- Documentation :
  - [Functional specification Drive folder]()

## Installation

> Dev purpose

- Prerequisites :\
Install [commitizen](http://commitizen.github.io/cz-cli/) globally

```sh
npm install commitizen -g
```

Read more at [Best practices section](#best-practices)

> Run & Dev purpose

- Prerequisites :\
  Populate your `.env` file with secret values as below

```sh

```

- Install dependencies :

```sh
yarn install
```

## Local run

```sh
yarn start
```

To run the app in the development mode with hot reload use :
Then open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Tests

```sh
yarn test
```

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

## Build

```sh
yarn build
```

## Deploy

The app will be deployed on .

## Formatting

To use formatting on VS Code please install these plugins : [](), [Eslint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) and [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode).\
Follow Prettier extension's instructions to setup "format on save" for ease of use.

## Best practices

- For commit and repository consistency, please use :

```sh
git cz # instead of 'git commit'
```

You'll be prompted to fill in any required fields and your commit messages will be formatted according to the standards defined by project maintainers.

- Respect the [git-flow process](https://danielkummer.github.io/git-flow-cheatsheet/index.fr_FR.html) as much as possible :

- Create a branch for each features - eg. `feature(user): create profil` or `fix(room): update room name`
- Commit with `giz cz`
- Submit PR to `develop` branch

## Naming convention

### Files naming

- Folders : kebab-case or spinal-case, eg : `my-components`
- Assets (Pictures, css files, logos, ...) : kebab-case or spinal-case, eg : `my-logo.svg`
- React components : PascalCase or UpperCamelCase, eg : `MyComponent.js`

### Variables and classes naming

- HTML : kebab-case or spinal-case - eg : `my-hmtl-component`
- CSS : kebab-case or spinal-case - eg : `my-css-class`
- JS functions and variables : camelCase - eg : `myFunction` or `myVariable`
- Framework components and JS classes : PascalCase or UpperCamelCase - eg : `MyComponent` or `MyClass`

## Resources

- Main Framework :
- UI components framework :
- UI icons library :

## Learn More
