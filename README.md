# Neat
Neat is an advanced WordPress Base theme which uses Gulp, Sass etc. with auto theme package builder.

![Neat](https://i.imgur.com/Db366oR.jpg)

## Features

- Saas
- Gulp
- Bower
- Custom architecture design
- Theme zip file build with Gulp
- Lean PHP files with next to no syntax

## Getting Started

1. Grab a copy of this theme or Clone this theme, E.g. go to the themes folder then run `git clone https://github.com/ahmadawais/neat neat`

2. You need Node.js & NPM installed if you haven't installed it, go ahead and install [Node.js](https://nodejs.org/en/download/) first. Once you have Node installed, the next steps are simple enough.

3. Install the Dependencies — Open a command prompt/terminal and navigate to your theme's root directory and run this command: `npm install` - This installs all the necessary Gulp plugins to help with task automation such as Sass compiling and browser-sync! You'll need to run this step on each of your projects, going forward.

4. Set your project configuration in `gulpfile.js`!! Be sure to go into `gulpfile.js` and setup the project configuration variables. This is important for using Browser-Sync with your project. Make sure in `gulpfile.js` that you set the project variable to the appropriate name for your project URL. Default is "`yourlocal.dev`"


4. Install Bower - In the command prompt/terminal run this command: `npm install -g bower`. This installs Bower (the -g flag installs globally, not just in the current directory, super friends). Your only need to do this step once.


5. Run `gulp` command in the root folder of your theme and it will start generating CSS from Sass and everything else

6. Run `gulp images` to optimize images and only place the images in `assets/img/raw/` folder, they'll moved to `assets/img/` once optimized

7. To build an installable zip file of your theme, use command `gulp build` and your project.zip file will be created as well as a `buildTheme` folder, where you can see what was zipped.

## License
Released under GPL v2.0
