# mini shop project build with symfony 4 and react js 
#library  used
.MobX  js library
.jsPDF library

#Getting started
git clone https://github.com/fmathlouthi/aa.git

// change directory
cd aa

// install dependencies
composer install

yarn install or yarn upgrade

.src/Controller/DefaultController.php: this Controller handles all HTTP requests sent to the application.
.templates/default/index.html.twig: this template will render the React application within Symfony by binding the React app to the div with an id of root.
.assets/js: this directory holds all the React components for the application.



#run

yarn add mobx mobx-react --save-dev
yarn add @babel/plugin-proposal-decorators @babel/plugin-proposal-class-properties
yarn run watch

symfony serve

