# Override Class Declarations By Styling ID Attributes

### DESCRIPTION
* CSS styles apply from top to bottom inside the `style` tags. We can override the `class selector` styling by `id selector` styling. Even if `id selector` is written anywhere inside the `style` tags.
* In below example, *orange-text* `id selector` overrides the *blue-text* `class selector`, So the `h1` element text becomes orange. 
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
        <h1 id="orange-text" class="pink-text blue-text">Hello World!</h1>
    </body>
```

### CODE
[Click to view the code.](override-class-declarations-by-styling-id-attributes.html)

### OUTPUT
[Click to view the output.](http://htmlpreview.github.io/?https://github.com/saipothanjanjanam/freecodecamp-full-stack-dev/blob/master/Responsive_Web_Design_Certification/2.Basic_CSS/29.Override_Class_Declarations_By_Styling_ID_Attributes/override-class-declarations-by-styling-id-attributes.html)
