###  project 

Pattern Library 

I am using OOCSS (Modules), Atomic CSS (clean code base) and SMACSs (file structure) and BEM (Naming convention). 

The site is built with includes so each component can be removed without affecting the remainder of the page.  Want to include a testimonail- Include it in the .html file add it to the pug files and scss files. 

This is going to be a modular system built ontop of prebuilt UI cards that can be added to the project to quickly prototype a layout. 

Each component has minimal styling and uses atomic css for general stytling this is prefixed with a. 

```css
.a-propertyName{ }
```
The leading principle is that this pattern library is not defined by a grid system. Add the css classes to your html markup and the UI element will comply with the grid, grid system or grid frame work that you are using. 


## Responsive 

Every UI I component is build with a mobile first approach and extremely customizable to adobt to the breakpoints for different projects

Base Atomic CSS     
=============================

This is the start of the Base Atomic CSS for rapid prototyping. The idea behind this project is to provide a base set of utility classes that can be eaisily added to a new or existing project. It is designed to be modular so if you dont use a set of utility classes remove it from the import statement on the _utility-dir.scss file. 


This is a starter file that inludes: 
1. Jekyll 
2. Gulp
    Browser sync 
    Autoprefix
    Pug 
3. Atomic utlility classes 


### Margin

```css
.margin-auto: 0 auto; 
```

## Flexbox 

```css
.flex{ display: flex;}

.flex-r{ flex-direction: row; }

.flex-c{ flex-direction: column; }

.flex-rr{ flex-direction: row-reverse; }

.flex-cr{ flex-direction: column-reverse; }



// Justify-Content
.just-start{ justify-content: flex-start;}

.just-end { justify-content: flex-end;}

// Align -items 
.align-start { align-items: flex-start;}

.align-end { align-items: flex-end;}


// Flex-Wrap 
.flex-wrap { flex-wrap: wrap;}

```

## Position
```css
.relative { position: relative; }

.absolute { position: absolute;}

.fixed { position: fixed;}
```

## Text
```css
.txt-l{ text-align: left; }

.txt-r{ text-align: right;}

.txt-c{ text-align: center; }

.txt-dec-none { text-decoration: none; }
```

## Display
```css
.block{ display: block}; 

.block-in{ display: inline-block}; 

.none{ display: none}; 

.block{ display: block}; 



```

## colors
```css
.off-white{ background-color: #F0FFFF; }

.white{ background-color: #FFFFFF; }

.black{ background-color: #000000; }

.aqua{ background-color:#00FFFF; }

.cyan{ background-color: #00FFFF; }

.crimson{ background-color: #DC143C; }

.dark-orange{ background-color: #FF8C00; }

.deep-pink{ background-color: 	#FF1493; }

.light-blue{ background-color: 	#bfd7ff; }

.pale-green{ background-color: 	#b5e0b1; }

.army-green{ background-color: 	#699165 }

.dark-red{ background-color: 	#681a0a; }

.gold{ background-color: 	#aa721e; }




```

### OverFlow 
```css
.overflow-h { overflow: hidden; }

.overflow-x-s { overflow-x: scroll; }

.overflow-y-s { overflow-y: scroll; }
```


### list
```css
.list-sn { list-style: none; }
```