Steps to start a React project 
    npm init (to generate a package.json file)
    install dependencies: (main dependencies & dev dependencies):
        Main dependencies:
            npm install express (back-end)
            npm install mangodb (back-end)
            npm i react react-dom (front-end)
        
        Dev dependencies:
            npm i -D webpack webpack-cli (translate module code into things browsers can understand)
            npm i -D babel-loader @babel/cli @babel/core @babel/preset-env @babel/preset-react @babel/plugin-proposal-class-properties (loader)
            npm i -D nodemon (auto restart nodes)
            npm i -D eslint babel-eslint eslint-plugin-react
            npm i -D prop-types (react package)

    Now add scripts to package.json
        start: nodemon --exec babel-node server.js --ignore public/ (make server code understand js for server item rendering)
        dev: webpack-wd (change source file into a bundle file which can be understood by the browser) (watch and dev flag)
    
    Create config files for webpack and babel
        webpack.config.js
        babel.config.js
        eslint.rc.js



