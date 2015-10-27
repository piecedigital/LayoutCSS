#Understanding Semantics

LayoutCSS makes it easy to know what you're using and what it's doing. Almost every class is similar to their corresponding CSS property. This method of semantics aims to eliminate the trouble of having to recall what a chosen class does because its role is so explicit.

The main unique thing about LayoutCSS that you should know is how number values work. Pretty much, numbers in the classes are represented like float values, but instead of a period (because you can't do that with CSS) it's an underscore. The resulting value from the this type of class is equal to `float * 16`.

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