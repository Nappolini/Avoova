###  project 

Pattern Library 

I am using OOCSS (Modules) SMACSs (file structure) and BEM (Naming convention). 

The site is built with SASS includes so each component can be removed without affecting the remainder of the page.  Want to include a testimonail- Include it in the .html file add it to the pug files and scss files. 

This is going to be a modular system built ontop of prebuilt UI cards that can be added to the project to quickly prototype a layout. 

Each component has minimal styling and uses atomic css for general stytling this is prefixed with a. 


The leading principle is that this pattern library is not defined by a grid system. Add the css classes to your html markup and the UI element will comply with the grid, grid system or grid frame work that you are using. 


## Responsive 

Every UI I component is build with a mobile first approach and extremely customizable easily change the responsive break points to suit your UI design. 

Base Atomic CSS     
=============================

This is the start of the Base Atomic CSS for rapid prototyping. The idea behind this project is to provide a base set of utility classes that can be eaisily added to a new or existing project. It is designed to be modular so if you dont use a set of utility classes remove it from the import statement on the _utility-dir.scss file. 


This is a starter file that inludes: 
1. Jekyll 
2. Gulp
    Browser sync 
    Autoprefix
    Pug 
    
Items that will be added to the gulp file include; 
1. Babel for ES6
2. Image minification
3. CSS minification 



