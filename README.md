# Bare-Bone-Structure-For-Web-Application
Bare Bone Structure For Web Application
This a bare bone structure for any Web application it is Based on MVC architecture. we are using node.js 
.This explains the basic steps . Look at the documentation of each step for the precise step of how it is to be done.

Steps ..
1) NPM init.(To initialize the node js )
	Our main file is server.js
2)install Express server and jade locally using the following commands
	npm install express --save
	npm install jade --save
3)Create a server.js file in the main Folder
	and require the server and initialize it
4)create a folder named server inside the main folder
5) create a view folder in the server folder to store all the view files 	
	the views folder will have all jade files to be viewd on the screen
	set the express server to look for jade files in server/views
	set the view engine as jade
6)Create a static public folder to store all the static files such as the css files etc in the main directory
7) intall bower globally to install front end dependencies
8) initalize  bower using bower init
9) create folder named vendor to install all the front end dependencies 
10)Create a .bowerrc file to set the directory of install to public/vendors
11)Install the front end dependencies which are Bootstrap ,Jquery locally
12)Install grunt globally
13)Intall grunt ,grunt-contrib-sass,Grunt watch locally using npm
14)Create a gruntfile.js in root directory for grunt configuration
15) set the location of conversion of scss files to css files and the location where to search for the scss files. Load the contrib-sass and contrib-watch files using grunt.loadNpmTasks();
16)If Sass is not installed .Install ruby first and then sass.
17)Create a folder src inside the server folder which will have the scss files
18) Create a main.scss inside src folder
19)Create a css folder inside the public folder which will contain the main.css file
20)Create a .gitignore file which will ignore the files which are not to be pushed like node_modules ,Public/vendor
21) Install nodemon globally