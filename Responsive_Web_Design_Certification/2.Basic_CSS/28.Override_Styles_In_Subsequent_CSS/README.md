# Override Styles in Subsequent CSS

### DESCRIPTION
* If there are more styles conflicting each other for the same element i.e style by `style-1`(class-1) and `style-2`(class-2) for element then, the style (`style-2`) which comes the later inside the `style` tags will overrides the previous (`style-1`).
* In the below code, `h1` element has two styles, one by `pink-text` and other by `blue-text`. Then as the `blue-text` class came later the `pink-text` class inside the `style` tags (*browser reads CSS from top to bottom*), Therefore it overrides the `pink-text` class and the text of `h1` becomes `pink` color.
```html
    <style>
        body {
            font-family: monospace;
            color:green;
            background-color:black;
        }
        .pink-text{
            color:pink;
        }
        .blue-text{
            color:blue;
        }
    </style>
    <body>
        <h1 class="pink-text blue-text">Hello World!</h1>
    </body>
```

### CODE
[Click to view the code.](override-styles-in-subsequent-css.html)

### OUTPUT
[Click to view the output.](http://htmlpreview.github.io/?https://github.com/saipothanjanjanam/freecodecamp-full-stack-dev/blob/master/Responsive_Web_Design_Certification/2.Basic_CSS/28.Override_Styles_In_Subsequent_CSS/override-styles-in-subsequent-css.html)
