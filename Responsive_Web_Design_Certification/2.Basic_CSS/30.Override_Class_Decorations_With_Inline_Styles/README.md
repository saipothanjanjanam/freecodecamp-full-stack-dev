# Override Class Declarations With Inline Styles

### DESCRIPTION
* We can override the `id selector` styling by `inline` styling.
* In below example,`inline` styling to the `h1` element overrides the *orange-text* `id selector`.
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
        #orange-text{
            color:orange;
        }
    </style>
    <body>
        <h1 style="color:white;" id="orange-text" class="pink-text blue-text">Hello World!</h1>
    </body>
```

### CODE
[Click to view the code.](override-class-declarations-with-inline-styles.html)

### OUTPUT
[Click to view the output.](http://htmlpreview.github.io/?https://github.com/saipothanjanjanam/freecodecamp-full-stack-dev/blob/master/Responsive_Web_Design_Certification/2.Basic_CSS/30.Override_Class_Decorations_With_Inline_Styles/override-class-declarations-with-inline-styles.html)
