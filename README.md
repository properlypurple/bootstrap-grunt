bootstrap-grunt
===============
This is a sample setup for creating simple bootstrap projects with Grunt.js. 
#Usage#
+ Install nodejs>=0.10 and npm
+ Install grunt-cli globally  `sudo npm install -g grunt-cli`
+ clone the repo, cd to the directory and run `npm install`. This will install the grunt modules required.
+ make changes to assets/less/\* and assets/js/\* annd run grunt to compile.
+ Edit Gruntfile.js to comment out any js file you don't want to include in your project.
+ Edit assets/less/bootstrap/bootstrap.less to comment out any less file you don't want.
+ Write your own less in app.less and your own js in _main.js.
+ If you want to compile less and js in realtime, run `grunt watch` in the terminal.
