# C&A Brasil Storefront Styleguide
*Styleguide for HTML, CSS and JS development*

## HTML Templates

### Template names

### Formating

* Indent using spaces instead of tabs. Use the editor config file.

* Use 4 spaces for indentation.

    **Don't**
    ```html
    <a href="#">
        <span></span>
    </a>
    ```

    **Do**
    ```html
    <a href="#">
        <span></span>
    </a>
    ```

* Use dashes over camelCasing in class names.

    **Don't**
    ```html
    <div class="productImage">
        ...
    </div>
    ```

    **Do**
    ```html
    <div class="product-image">
        ...
    </div>
    ```
***

* If an element wraps other(s) element(s) write the nested elements in a new line

    **Don't**
    ```html
    <a href="#"><span></span></a>
    ```

    **Do**
    ```html
    <a href="#">
        <span></span>
    </a>
    ```

* If an element has only text inside it it's not necessary to write the text in a new line

    **Do**
    ```html
    <a href="#">Comprar</a>
    ```

    **Do**
    ```html
    <a href="#">
        Comprar
    </a>
    ```

* If an element wraps text and other element(s) write them in a new line

    **Don't**
    ```html
    <a href="#">Comprar
        <i class="icon-bag"></i>
    </a>
    ```

    **Do**
    ```html
    <a href="#">
        Comprar
        <i class="icon-bag"></i>
    </a>
    ```

## CSS

### Formatting

* Use 4 spaces for indentation.

    **Don't**
    ```css
    .menu {
      background: blue;

      .menu-item {
        // ...
      }
    }
    ```

    **Do**
    ```css
    .menu {
        background: blue;

        .menu-item {
            // ...
        }
    }
    ```

* Use dashes over camelCasing in class names.

    **Don't**
    ```css
    .productName {
        // ...
    }
    ```

    **Do**
    ```css
    .product-name {
        // ...
    }
    ```

* Avoid using id selectors

    **Avoid**
    ```css
    #my-component {
        // ...
    }
    ```
    **Prefer**
    ```css
    .my-component {
        // ...
    }
    ```

* When using multiple selectors in a rule declaration, give each selector its own line.

    **Don't**
    ```css
    header,footer {
        // ...
    }
    ```

    **Do**
    ```css
    header,
    footer {
        ...
    }
    ```

* Put a space before the opening brace `{` in rule declarations

    **Don't**
    ```css
    .product-name{
        ...
    }
    ```

    **Do**
    ```css
    .product-name {
        ...
    }
    ```

* In properties, put a space after, but not before, the `:` character.
    
    **Don't**
    ```css
    font-weight:bold;
    ```

    **Do**
    ```css
    font-weight: bold;
    ```

* Put closing braces `}` of rule declarations on a new line

    **Don't**
    ```css
    .product-name{
        ...}
    ```

    **Do**
    ```css
    .product-name {
        ...
    }
    ```

* Put blank lines between rule declarations



### SASS


***

## Javascript


## Icons

### Icon names

* Icons should be named as what they are and not what they could represent

