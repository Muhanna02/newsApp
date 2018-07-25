Documentation
http://bit.ly/ionicthemes-ion2fullapp

Workflow
##To run your app in the browser (great for initial development): ionic serve

##To run on iOS: ionic run ios

##To run on Android: ionic run android

##Review ionic CHANGELOG when updating ionic-angular version https://github.com/driftyco/ionic/blob/master/CHANGELOG.md

Configs
Cordova (uses config.xml)
Mass saving platforms on an existing project
cordova platform save Use it when you have a pre-existing project and you want to save all the currently added platforms in your project.

Ionic (uses package.json)
Clean and install
ionic state reset This will remove everything then bring back what you have specified in the package.json file.

Store current state
ionic state save To store the current platforms and plugins to the package.json

Restore current state
ionic state restore This will add in the appropriate plugins and platforms from the package.json

newsApp
