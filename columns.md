#Columns and Responsive Columns (DEPENDENT)

##Dependencies (responsive columns)
* _x-padding.scss
* _y-padding.scss
* _border-radius.scss

##Available styles

#####Responsive Styles
* **.col-4-3-2-1**
* **.col-4-2-1**
* **.col-4-2**
* **.col-3-2-1**
* **.col-2-1**

#####Static Styles
* **.col-2**
* **.col-3**
* **.col-4**

> Sets a given element as a column with an indicated break point

> A break point is a percentage-based partition of its parent element

> E.G., col-4 will take up 25% of its parent element

> With the "_columns-responsive-DEP.scss" col-4-3-2-1 will have break points at 25%, 33%, 50%, and 100%

> Column classes with only one break point are not dependent on "_columns-responsive-DEP.scss"

######Usage
``` html
<div class="col-2">...</div><div class="col-2">
</div>
```