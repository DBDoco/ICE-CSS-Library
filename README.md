<h1 align="center">
  ICE - CSS Library
  <br>
</h1>

<h4 align="center">Lightweight CSS Library made with <a href="https://sass-lang.com">SASS</a> and inspired by <a href="https://getbootstrap.com">Bootstrap</a>.<a href="https://gulpjs.com">Gulp.js</a> is used for compiling sass files to css and for debuging. Library can be used for multiple html pages inside of the work directory.</h4>

<p align="center">
  <img src="https://media4.giphy.com/media/bfDjEUX11WQs3072iw/giphy.gif?cid=790b761166f062b4ff2272e0bad3231cfb9cbdff3afd6cd1&rid=giphy.gif&ct=g" alt="ice" />
</p>

<div align="center">
  <h3>
    <a href="">
      Showcase
    </a>
    <span> | </span>
        <a href="">
      Prototype Page
    </a>
</h3>
</div>

## Features

#Components
👉 Button (ex. .btn-"color", .btn-outlined-"color", .btn-complement-"color")
👉 Card (includes: .card-title, .card-body)
👉 Navbar (includes: .navbar-title)

#Colors
👉 Dark and white variations for each color (ex. .text-"color"-dark-"1-9")
👉 "primary"
👉 "secondary"
👉 "error"
👉 "info"
👉 "blue"
👉 "red"
👉 "yellow"
👉 "green"
👉 "orange"
👉 "purple"
👉 "gray"
👉 "black"
👉 "white"

#Text
👉 Font sizes (ex. font-size-sm, font-size-lg, .font-size-xl, .font-size-xxl)
👉 Colors for text and background of text (ex. .text-"color", .bg-"color"-light-"1-9")
👉 Hover effects (ex. .text-hover-"color")

#Breakpoints
👉 Extra small
👉 Small
👉 Medium
👉 Large
👉 Extra large

#Utilities
👉 Padding (Padding left, right, top, bottom) (ex. .pl-1, .pr-2)
👉 Margin (Margin left, right, top, bottom) (ex. .ml-1, .mr-2)
👉 Opacitiy (ex. .0-20, .0-10)
👉 Border-radius (ex. .br-xs, .br-full)
👉 Display (ex. display-f, display-n)
👉 Font size (ex. .font-size-sm, .font-size-md)

#Grid system
Similiar to Bootstrap grid, devided by rows and columns.
👉 ex. .col-"1-12"-xs, .col-"1-12"-md
👉 Grid gap (ex. .gap-"1-3")


## Optimization
Gulp compiles all css classes which are then purged by gulp.purgecss package. Basically all classes that aren't used in html file are deleted.

## Customization
All default library definitions can be overriden in the ./sass/index.scss file. Write overrides above the "@import 'ice'" line.


## How To Use

Clone this repository
```bash
$ git clone https://github.com/DBDoco/ICE-CSS-Library.git
```

Go into the repository
```bash
$ cd ICE-CSS-Library
```

Install dependencies
```bash
$ npm i
```

Compile
```bash
$ gulp
```

