# HSC Programming Club
## Getting Started
First, make sure you have installed [node](https://nodejs.org/en/) using [nvm](https://github.com/nvm-sh/nvm). If you are using Windows, I recommend [setting up Windows Subsystem for Linux](https://docs.microsoft.com/en-us/windows/wsl/install). Then [clone](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) this repository. Once cloned, run the following command to install required Node.js packages.
```bash
$ npm install
```
Now you can start a testing server that will automatically reload as you make changes.
```bash
$ npm start
```
To build the site for production
```bash
$ npm run build
```
which will place the bundled files in the `./dist` directory.

_The API urls are different for development and production. The switch is handled automatically by vite environment variable._