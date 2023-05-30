# ProjectsTemplate
This is Template for Frontend Projects.

<h1> This is a template for projects </h1>
<p>For starting a project you mast have to inherit all tools in it. Like git, babel, prettier, and eslint, node, npm etc</p>
<h3> First you have to ready your workspace for the project<h3>
<p> Go to workspace in vscode setting, and type formatter, than set prettier as a default formatter. Now you will see .vscode folder is opened in your project. In this folder you will see a file name setting.json, </p>
  <>
  in setting.json put below codes. </br>
    { <br />
  "editor.defaultFormatter": "esbenp.prettier-vscode", <br />

  "editor.formatOnSave": true, <br />
  "[javascript]": { <br />
    "editor.formatOnSave": false, <br />
    "editor.defaultFormatter": null <br />
  }, <br />
  "[javascriptreact]": { <br />
    "editor.formatOnSave": false, <br />
    "editor.defaultFormatter": null <br />
  }, <br />
  "javascript.validate.enable": false, //disable all built-in syntax checking <br />
  "editor.codeActionsOnSave": { <br />
    "source.fixAll.eslint": true, <br />
    "source.fixAll.tslint": true, <br />
    "source.organizeImports": true <br />
  }, <br />
  "eslint.alwaysShowStatus": true, <br />
  // emmet
  "emmet.triggerExpansionOnTab": true, <br />
  "emmet.includeLanguages": { <br />
    "javascript": "javascriptreact" <br />
  } <br />
} <br />

  </>
  <br/>
  <h5>Setup Preitter</h5>
  create .prettierrc.json and put below codes <br/>
  <p>
       { <br/>
        "semi": true, <br/>
        "trailingComma": "es5", <br/>
        "tabWidth": 4, <br/>
        "printWidth": 80, <br/>
        "bracketSameLine": true, <br/>
        "arrowParens": "always", <br/>
        "singleAttributePerLine": true, <br/>
        "singleQuote": true <br/>
      } <br/>

  </p>
  
 <h1>Eslint setup</h1>
  <p> First download prettier and eslint extention </p>
  
<h3> For Inherit eslint in project first put this below command</h3>
  
<b>  npm init -y or npm init --yes  </b>
it will be ready package.json file
after that put this command:
<b> npm init @eslint/config </b>  
<h6> You will be asked more questions about project in terminal give all answers, after that .eslintrc.js and package-lock.json will be created </h6>
In .eslintrc.js you can put many custom rules. Now You should past below rules in .eslintrc.js
<p>
     rules: {  <br/>
            'no-plusplus': 'off', <br/>
            'no-console': 0, <br/>
            indent: 0, <br/>
            'no-unused-vars': 'off', <br/>
            'vars-on-top': 'off', <br/>
            'no-var': 0, <br/>
        }, <br/>
</p>
<footer> Now linting is ready for projects</footer>



