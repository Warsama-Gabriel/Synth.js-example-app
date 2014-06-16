Synth.js-example-app
====================

WDI Research project

Synth is a back end web framework designed to make angular apps easy and fun to create and manage all in one package.

Some great features about synth is that it handles installing our back and front end package dependencies and organizes them into easy folders for us to work with.

It generates a minimal restful api with little code that can work alongside our html and javascript in the same folder.
Synth also cleverly organizes our application folder into two distinct categories. The front category holds our app javascript and html data as well as any front end libraries we are using. The back end category allows us to configure out database and api to repond to requests made by the client. This way we have a nice neat package for our angular apps and no need for external back end frameworks or seperate api's.

Synth.js is built ontop of tried and tested technologies such as node.sj and express.


So I heard about this awesome framework called Angular...nothing could go wrong right??

Wrong. The problem with Angular is that it only returns a rendered layout of html and has to take another trip back to fetch the data attached to that html. This creates a problem because our app has to make two trips to the server before we can get the right data back. This might not seem like such a huge problem at first but when we think about adding complexity to our angular js apps and coupled with notion that sometimes we are trying to connect to servers very far away, this becomes a problem.

Synth Js solves this problem with us because it gives the client everything it needs in one snap which saves our app from making multiple trips to the server. The way synth Js does this is by returning data embedded inside the html that is returned as JSON.


Instructions on how to use Synth .JS

Setup 

Dependencies

You'll need to have these installed before we can use synth.

Node ver. 0.10.0 or higher - Available for free here
NPM ver. 1.3 or higher (It should automatically be installed with Node these days)
MongoDB - Available for free here - Don't forget to launch it in the backgroound after installing it.


Once you've installed mongo and have it running type this into an open shell.

npm install -g synth

This will create a new folder with all the nescessary data for your angular js app.

You can add external libraires to the front and back end components using these commands

synth install -b # Install third-party back-end packages (using npm)
synth install -f # Install third-pary front-end packages (using bower)

