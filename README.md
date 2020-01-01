##1- Install angular cli : npm install -g @angula/cli
##2- create new project : ng new tdd-angular
        * Add angular Routing? No
        * Which stylesheet format whould you like to use ? Less
##3- cd tdd-angular
##4- ng g c src/components/header
##5- ng g c src/components/homes
##6- Update the main html component to use the new components:
        <app-header></app-header>
        <app-homes></app-homes>
##7- Run the project : ng serve
##8- install uikit framework with jquery (because its a dependancy ): npm i jquery uikit
##9- Go to angular.json in the project folder and add Jquery under the scripts section:
            "node_modules/jquery/dist/jquery.min.js",
            "node_modules/uikit/dist/js/uikit.min.js",
            "node_modules/uikit/dist/js/uikit-icons.min.js"
