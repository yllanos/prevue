# Prevue #
VueJS app boilerplate for large scale component-based development. Supporting Webpack+Bootstrap+EcmaScript 6

## Prerequisites ##
I strongly recommend to globally install eslint, gulp-cli and webpack before cloning this:

`npm install -g eslint gulp-cli webpack`

## Clone this project ##
`git clone https://github.com/yllanos/prevue.git`

## Usage ##

``` bash
$ cd prevue
$ npm install
$ npm run dev
```

### Run development server ###
`npm run dev`

### Production build ###
`npm run build`

## Project structure ##
``` bash
├── LICENSE
├── README.md
├── gulpfile.js
├── index.html								                #Base HTML file	
├── index.js								                  #This is the bundled JS file
├── package.json                              #Project, scripts and dependencies config
├── src										                    #Code goes here	
│   ├── components							              #Components directory
│   │   └── app-component					            #Sample component dir
│   │       ├── app-component-template.html	  #Sample component template
│   │       ├── app-component.js			        #Sample component JavaScript
│   │       └── logo.png					            #Sample component JavaScript
│   └── main.js								                #Container JS file
└── webpack.config.js                         #webpack config file
```

### `./index.js`
A bundled index.js file will be created on root. This file will be transpiled from EcmaScript 6 components referenced from /src/main.js into EcmaScript 5.1


# Have fun! #
Go ahead and create your own components
