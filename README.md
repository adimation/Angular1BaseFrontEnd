# angular-front-end

This project is generated with [yo angular generator](https://github.com/yeoman/generator-angular)
version 0.15.1.

## Build & development

Install `NodeJS`

Run `npm install -g yo grunt-cli grunt bower`

Run `npm install -g generator-angular` Yeoman angular generator

Run `yo angular appName` generate angular app with your app name by replacing 'appName'

paste in bower.json following lines
{
    "directory": "app/components",
    "json": "bower.json" // Add this line
}
Also make changes in Gruntfile.js replacing bower_components to app/components

Run `npm install` `npm bower install` to install npm and bower dependencies

Run `grunt` for building and `grunt serve` for preview.

## Testing

Running `grunt test` will run the unit tests with karma.
