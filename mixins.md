# Mixins

## Description

These mixins generally have extra code in them with vendor prefixes. Use these mixins in your custom styles.

## Available styles

* **@mixin border-radius($val...)**

> Adds `border-radius` to a style with a given value

> Treat it, the value(s), the same as you would manually writing the style property value

> Has vendor prefixes

###### Usage
``` sass
{
	@include border-radius(10px);
}
```
``` sass
{
	@include border-radius(10px, 10px);
}
```


* **@mixin box-shadow($val...)**

> Adds `box-shadow` to a style with a given value

> Treat it, the value(s), the same as you would manually writing the style property value

> Has vendor prefixes

###### Usage
``` sass
{
	@include box-shadow(0 0 8px 0 black);
}
```


* **@mixin transformR($val...)**

> Adds `transform: rotate($val)1 to a style with a given value

> Treat it, the value(s), the same as you would manually writing the style property value

> Has vendor prefixes

###### Usage
``` sass
{
	@include transformR(90deg);
}
```


* **@mixin transformS($val)**

> Adds `transform: scale($val)` to a style with a given value

> Treat it, the value(s), the same as you would manually writing the style property value

> Has vendor prefixes

###### Usage
``` sass
{
	@include transformS(2);
}
```


* **@mixin transformRS($rot, $scale...)**

> Adds `transform: rotate($rot) scale($scale)` to a style with a given value

> Has vendor prefixes

###### Usage
``` sass
{
	@include transformRS(45deg, 1.5);
}
```


* **@mixin transformT($val...)**

> Adds `transform: translate($val)` to a style with a given value

> Has vendor prefixes

> Treat it, the value(s), the same as you would manually writing the style property value

###### Usage
``` sass
{
	@include transformT(-50$, -50%);
}
```


* **@mixin transformST($val1, $val2...)**

> Adds `transform: scale($val1) translate($val2)` to a style with a given value

> Has vendor prefixes

###### Usage
``` sass
{
	@include transformST(1, -50%, 0);
}
```


* **@mixin transformRT($val1, $val2...)**

> Adds `transform: rotate($val1) translate($val2)` to a style with a given value

> Has vendor prefixes

###### Usage
``` sass
{
	@include transformRT(180deg, 10px, 10px);
}
```


* **@mixin transformSRT($val1, $val2, $val3...)**

> Adds `transform: scale($val1) rotate($val2) translate($val3)` to a style with a given value

> Has vendor prefixes

###### Usage
``` sass
{
	@include transformSRT(3, 270deg, 50%, 50%);
}
```


* **@mixin media-min($val)**

> Creates a media query for "min-width" with a given value

> Has vendor prefixes

> Takes content inside of a block

###### Usage
``` sass
{
	@include media-min(1024px) {
		// content
	}
}
```


* **@mixin media-max($val)**

> Creates a media query for "max-width" with a given value

> Has vendor prefixes

> Takes content inside of a block

###### Usage
``` sass
{
	@include media-max(540px) {
		// content
	}
}
```


* **@mixin animation($name, $time, $itter)**

> Adds `animations` to a style with a given $name, running time ($time), and iteration type ($itter)

> Has vendor prefixes

> Treat it, the value(s), the same as you would manually writing the style property value

###### Usage
``` sass
{
	@include animation(bounce, 1s, infinite);
}
```


* **@mixin keyframes($val)**

> Creates `keyframe` for animation of a style with an animation of the given name

> Has vendor prefixes

> Treat it, the value(s), the same as you would manually writing the style property value

###### Usage
``` sass
@include keyframes(bounce) {
	// content
}
```


* **@mixin background-gradient($deg, $colors...)**

> Adds `background: linear-gradient` to a style with a given value

> Has vendor prefixes

> Treat it, the value(s), the same as you would manually writing the style property value

###### Usage
``` sass
{
	@include background-gradient(90deg, black, green);
}
```


* **@mixin linear-gradient($deg, $colors...)**

> Adds `background: linear-gradient` to a style with a given value

> Has vendor prefixes

> Treat it, the value(s), the same as you would manually writing the style property value

###### Usage
``` sass
{
	@include linear-gradient(90deg, black, green);
}
```


* **@mixin transition($val...)**

> Adds `transition` to a style with a given value

> Has vendor prefixes

> Treat it, the value(s), the same as you would manually writing the style property value

###### Usage
``` sass
{
	@include transition(.5s all);
}
```


* **@mixin appearance($val)**

> Adds `appearance` to a style with a given value

> Has vendor prefixes

> Treat it, the value(s), the same as you would manually writing the style property value


###### Usage
``` sass
{
	@include appearance(none);
}
```