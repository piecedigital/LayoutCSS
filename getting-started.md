# Getting Started

LayoutCSS makes it easy to know what you're using and what it's doing. Almost every class is similar to their corresponding CSS property. This method of semantics aims to eliminate the trouble of having to recall what a chosen class does because its role is so explicit.

The main unique thing about LayoutCSS that you should know is how number values work. Pretty much, numbers in the classes are represented like float values, but instead of a decimal (because you can't do that with CSS) it's an underscore. The resulting value from the this type of class is equal to `float * 16`.

For example:

``` sass
.x-pad-1_0
```

equals

``` sass
padding-left: 1.0*16px;
padding-right: 1.0*16px;
```

which means the result is

``` sass
padding-left: 16px;
padding-right: 16px;
```

Fairly simple clear, right?

This level of clarity is something you can come to expect from LayoutCSS.

___

# Modularity

LayoutCSS is written in Sass(SCSS) and is broken up into several separate modules. You can `@import` these modules as needed. The default `style.scss` file that comes with LayoutCSS has every module included by default, and some predefined media queries (created from the LayoutCSS `_mixins.scss` module ;) ), so you may want to look through the file to see what you need and don't need. It's also laid out in a way that I like to write my Sass but feel free to switch things up, or start from scratch!
___
# Dependencies

Some modules are dependent on other modules. This is indicated by an all caps "DEP" at the end of a file name (e.g., `_module-DEP.scss`)
___

Visit the directory to view the specifications of the classes.
___

# Directory

* [Options](https://github.com/piecedigital/layoutcss/wiki/options)
* [Border Box](https://github.com/piecedigital/layoutcss/wiki/border-box)
* [Border Radius](https://github.com/piecedigital/layoutcss/wiki/border-radius)
* [Margins](https://github.com/piecedigital/layoutcss/wiki/margins)
* [Paddings](https://github.com/piecedigital/layoutcss/wiki/paddings)
* [Buttons](https://github.com/piecedigital/layoutcss/wiki/buttons)
* [Columns](https://github.com/piecedigital/layoutcss/wiki/columns)
* [Font Size](https://github.com/piecedigital/layoutcss/wiki/font-size)
* [Widths and Heights](https://github.com/piecedigital/layoutcss/wiki/widths-and-heights)
* [Mixins](https://github.com/piecedigital/layoutcss/wiki/mixins)
* [Positions](https://github.com/piecedigital/layoutcss/wiki/positions)