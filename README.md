# ng-seed
Seed project for enterprise-grade Angular applications without test files.

This project was generated with [angular-cli](https://github.com/angular/angular-cli) `--minimal` flag. The cli is configured to not generate `.spec` files and use inline-styles where possible.

## Usage
- Clone or download the repo
- Rename the project name `ngdemo` in:
  - package.json
  - angular-cli.json
  - index.html `<title></title>`
- Run `npm i`

## Structure
```
|-- node_modules
|-- src
  |-- app
  |-- assets
  |-- environments
  |-- shared
      |-- components
      |-- models
      |-- services
      |-- validators
      |-- guards
      |-- utils
```