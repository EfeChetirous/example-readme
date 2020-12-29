# Angular Quick Readme

This is a the template ready readme file for your Angular projects. Feel free to use.

## -Project Name-

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version x.x.x.

## Getting started

### Clone the repo

```shell
git clone https://github.com/username/xxx-project-name-xxx
cd intern-angular
```

### Install npm packages

Install the `npm` packages described in the `package.json` and verify that it works:

```sh
cd xxx-project-name-xxx
npm install
npm start or ng serve
```

After the `npm start` or `ng serve` command, The application will up on ` https://localhost:4200` . If you want to use different port like 5000 instead of 4200 , use `ng serve --port 5000` command or edit those lines in **angular.json** in the root directory.

```javascript
"serve": {
 "builder": "@angular-devkit/build-angular:dev-server",
 "options": {
  "browserTarget": "xxx-project-name-xxx:build",
  "port": 8080
 },
```

Shut it down manually with `Ctrl-C`.

#### npm scripts

These are the most useful commands defined in `package.json`:

* `npm start` - runs defined properties for the `start` command of the `scripts` object in `package.json` file.
* `npm run build` - runs the TypeScript compiler and asset copier once.
* `npm outdated` - the dependencies that are out of date can be discovered.
* `npm update` - perform safe dependency upgrades. Updates the packages in the `node_modules` folder, the `package.json` and `package-lock.json`files.
* `npm install <packagename>@latest` - upgrade to the latest major version of a package.

These are the test-related scripts:

* `npm test` - builds the application and runs intern tests (both unit and functional) one time.
* `ng test` - Runs unit tests via Karma in a project.
