# UI5-project-template

This project describes how to prepare your development environment when starting a new SAPUI5 project.

VSCODE:
-------
We use VSCode as editor, so first download and install it : 
  - https://code.visualstudio.com/download
  - https://portapps.github.io/app/vscode-portable/#portable-setup
  
GIT Source Code Manager:
------------------------
Your UI5 project will be available on a GIT repository, so download and install GIT SCM:
  - https://git-scm.com/download/win
  
  
Node.js,NPM
-----------
Download node.js(includes npm) to enable your project to use powerfull pluggins such as grunt, babel...:
  -https://nodejs.org/en/download/
  
Grunt
-----
Grunt and its pluggins are node modules installed via npm.You can see : https://gruntjs.com/getting-started

Install grunt CLI via the following command:
npm install -g grunt-cli (as administrator)
This will allow you to run grunt from anywhere you want.

Now install grunt in your project:
npm install grunt --save-dev
The --save-dev option will add grunt as dev dependancy in the package.son file.



  
