# C&A Brasil Storefront Styleguide
*Styleguide for HTML, CSS and JS development*

## HTML Templates

### Template names

* Template names should be writed in lowercase and follow the format below.
    
    `{account name}-{role}-{specification|identifier}-{version}`

    Each value wrapped in braces above we will call them ***fields*** in this section.

    * Fields description

        #### account name ####
        Name of store or account will you use the template. Eg. cea or ceaoutlet
        
        #### role ####
        Component or where the template will be placed. Eg. home, product, landing.

        * Roles should be always write in English.

            **Don't**
            ```
            cea-produto.html (or cea-produto for VTEX template name)
            cea-categoria.html (or cea-categoria for VTEX template name)
            ```

            **Do**
            ```
            cea-product.html (or cea-product for VTEX template name)
            cea-category.html (or cea-category for VTEX template name)
            ```

        * Use underscore when a role inherits from another role. Eg. cea-showcase_colection inherits from cea-showcase.

            **Don't**
            ```
            cea-showcase-collection.html
            ```

            **Do**
            ```
            cea-showcase_collection.html
            ```

        #### specification or identifier (optional) ####
        Use this field when the template is specific for a page or a campaign, like a collection name. Eg. pablo_vittar, gig, quatro_mares

        #### version (option) ####
        Version of the template if it's not the first. Should be writed with the format `v{number}`. Eg. v2, v3, v4.

        **Don't**
        ```
        cea-product-new.html
        cea-home-v_2.html
        cea-department-v-4.html
        cea-category-v1.html
        ```

        **Do**
        ```
        cea-product-v2.html
        cea-home-v2.html
        cea-department-v4.html
        cea-category.html
        ```

    * Use underscore `_` if a field have spaces. Dashes `-` are used just to separate fields.

        **Don't**
        ```
        cea_product_v3.html
        cea_home-v2.html
        cea-showcase-collection-gig.html
        cea-landing-collection-quatro-mares.html
        ```

        **Do**
        ```
        cea-product-v3.html
        cea-home-v2.html
        cea-showcase_collection-gig.html
        cea-landing_collection-quatro_mares.html
        ```
    

* The template names sould be in English

    **Don't**
    ```
    produto.html
    ```

    **Do**
    ```
    product.html
    ```

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

* If an element wraps other(s) element(s), write the nested elements in a new line

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

* If an element has only text inside it, it's not necessary to write the text in a new line

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

* If an element wraps text and other element(s), write them in a new line

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



***

## CSS

### Formatting

* Use 4 spaces for indentation.

    **Don't**
    ```scss
    .menu {
      background: blue;

      .menu-item {
        // ...
      }
    }
    ```

    **Do**
    ```scss
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
    ```scss
    .product-name {
        // ...
    }
    ```

* Avoid using id selectors

    **Avoid**
    ```scss
    #my-component {
        // ...
    }
    ```
    **Prefer**
    ```scss
    .my-component {
        // ...
    }
    ```

* When using multiple selectors in a rule declaration, give each selector its own line.

    **Don't**
    ```scss
    header,footer {
        // ...
    }
    ```

    **Do**
    ```scss
    header,
    footer {
        ...
    }
    ```

* Put a space before the opening brace `{` in rule declarations

    **Don't**
    ```scss
    .product-name{
        ...
    }
    ```

    **Do**
    ```scss
    .product-name {
        ...
    }
    ```

* In properties, put a space after, but not before, the `:` character.
    
    **Don't**
    ```scss
    font-weight:bold;
    ```

    **Do**
    ```scss
    font-weight: bold;
    ```

* Put closing braces `}` of rule declarations on a new line

    **Don't**
    ```scss
    .product-name{
        ...}
    ```

    **Do**
    ```scss
    .product-name {
        ...
    }
    ```

* Put blank lines between rule declarations
    
    **Don't**
    ```scss
    .product-name {
        // ...
    }
    .product-price {
        // ...
    }
    ```

    **Do**
    ```scss
    .product-name {
        // ...
    }

    .product-price {
        // ...
    }
    ```



### SASS


***

## Javascript


## Icons

### Icon names

* Icons should be named as what they are and not what they could represent

