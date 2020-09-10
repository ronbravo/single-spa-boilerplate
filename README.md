# Single SPA Boilerplate - Sample Project

This project was build with the [Single SPA Boilerplate](https://github.com/ronbravo/single-spa-boilerplate) repo. A set of boilerplate configurations for working with the [Single SPA](https://single-spa.js.org/) framework. The boilerplates are broken out into separate branches with a desire to keep them as minimal as possible. Each branch should have it's own `README.md` file with specific instructions for working with that particular setup.

**NOTE:** You may want to replace the information in the `package.json` with the appropriate information about the maintaining organization or company.

## Install PM2

Make sure your system has [PM2](https://pm2.keymetrics.io/) the process manager used to easily bootup and run services and servers.

* command: `npm install pm2 -g`
* **NOTE:** This project should include a starter `pm2.config.orig.js` file that should be renamed to `pm2.config.js`. Use this file to add processes that this project should be aware of and will run.

### Common PM2 Commands

```
// Show the running processes and their status.
pm2 ls

// Run the pm2 project config.
pm2 start pm2.config.js

// Run a specific pm2 configed app fromt he project
pm2 start pm2.config.js --only <application-name>

```

For a list of more commands just visit this link.

## Cli Commands

```
// Clone the sample project.
git clone -b release/sample-project git@github.com:ronbravo/single-spa-boilerplate.git sample-project

// Clone the root app.
git clone -b release/root-app git@github.com:ronbravo/single-spa-boilerplate.git root-app

// Clone the sample app for Angular.
git clone -b release/sample-angular-v10-app git@github.com:ronbravo/single-spa-boilerplate.git sample-angular-app

```
