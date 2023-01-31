# ProjectsTemplate
This is Template for Frontend Projects.

<h1> This is a template for projects </h1>
<p>For starting a project you mast have to inherit all tools in it. Like git, babel, prettier, and eslint, node, npm etc</p>
<h3> First you have to ready your workspace for the project<h3>
<p> Go to workspace in vscode setting, and type formatter, than set prettier as a default formatter. Now you will see .vscode folder is opened in your project. In this folder you will see a file name setting.json, open this file and put below codes</p>
  <b>
        {
        "editor.defaultFormatter": "esbenp.prettier-vscode",
        "editor.formatOnSave": true,
        "[javascript]": {
          "editor.formatOnSave": true
        },
        "[javascriptreact]": {
          "editor.formatOnSave": true
        },
        "editor.codeActionsOnSave": {
          "source.fixAll": true
        },
        "eslint.alwaysShowStatus": true,
        "eslint.validate": [
          "javascript",
          "javascriptreact",
          "typescript",
          "typescriptreact"
        ]
      }
  </b>
 <h1>Eslint setup</h1>
  <p> First download prettier and eslint extention </p>
  
<h3> For Inherit eslint in project first put this below command</h3>
  
<b>  npm init -y or npm init --yes  </b>
it will be ready package.json file
after that put this command:
<b> npm init @eslint/config </b>  
<h6> You will be asked more questions about project in terminal give all answers, after that .eslintrc.js and package-lock.json will be created </h6>
<footer> Now linting is ready for projects</footer>



