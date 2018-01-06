# C&A Brasil Storefront Styleguide
*Styleguide for HTML, CSS and JS development*

## HTML Templates

### Template names

### Formating

* Use 4 spaces for indentation

**Bad**
```html
<a href="#">
  <span></span>
</a>
```

**Good**
```html
<a href="#">
	<span></span>
</a>
```

* Use dashes over camelCasing in class names.

**Bad**
```html
<div class="productImage">
	...
</div>
```

**Good**
```html
<div class="product-image">
	...
</div>
```

## CSS

### Formatting

* Use 4 spaces for indentation

**Bad**
```css
.menu{
  background: blue;
}
```

**Good**
```css
.menu {
  	background: blue;
}
```

* Use dashes over camelCasing in class names.

**Bad**
```css
.productName{
	font-size: 16px;
}
```

**Good**
```css
.product-name {
  	font-size: 16px;
}
```

* Do not use ID selectors
* When using multiple selectors in a rule declaration, give each selector its own line.
* Put a space before the opening brace `{` in rule declarations
* In properties, put a space after, but not before, the `:` character.
* Put closing braces `}` of rule declarations on a new line
* Put blank lines between rule declarations

## Javascript

