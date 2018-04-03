# Sirius task

This task uses:
* Pug as an HTML preprocessor
* PostCSS
* Babel for JavaScript
* Browserify for bundling

## How to start developing -
1- create a branch with your page-name or the feature you're adding 
	for example >> pages/karim, pages/ahmed, features/header, features/buttons
2- create a page named >> *yourname*.pug in *workflow/src/*
3- add your own sections in *workflow/src/includes/* and include inside your own page -- check karim.pug --
4- to open browser directly to your file :
	1- open *gulpfile.js*
	2- edit lines 173,195 to your page name
	3- save it 
- -if needed- add your styles in the right place w rbna ystor :D 
- !IMPORTANT before pushing to origin reverse changes made in step 4 -"karim.html"- or solve the conflict happened in gulpfile.js 