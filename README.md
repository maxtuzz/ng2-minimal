# ng2-minimal
An absolutely minimal Angular 2 seed project, with source maps support and based on npm scripts only. It includes the official Angular 2 Typescript typings.

# Purposes

The simplest possible setup for getting started with Angular 2. Ideal for quickly putting together a demo or for trying out a new concept.

# Technologies used

Besides Angular 2 and npm, this setup uses:

- Typescript
- SystemJs for module loading 

# Installation 

After cloning the repo, run the following commands:

    npm install
    npm start 
    
# Problems installing ?

npm installations sometimes fail. Its better in general to upgrade your npm to version 3, specially if running on a windows box. This will avoid problems with long paths. If you are having generic npm installation problems, try the following:

    rm -rf node_modules
    npm cache clean
    npm install
    npm start
    
After the installation is successful, open a browser at the following url:

    http://localhost:8080
    
And there you have it, a minimal Angular 2 App up and running. You're all set!

# Issues

If you find some problem with the setup, please open an issue and i'll follow up. If you can include the full error message and your npm and node version. Also can you link your repo with the issue as well, if its publicly accessible.

# Unit Testing
Check the official unit testing seed repo - https://github.com/juliemr/ng2-test-seed and the corresponding talk [Testing strategies with Angular 2](https://www.youtube.com/watch?v=C0F2E-PRm44).


