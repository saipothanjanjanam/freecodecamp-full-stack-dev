# Prioritize One Style Over Another

### DESCRIPTION
* If the element has style by `body` element and `seperate style` for element itself then, `seperate style` for the element overrides the style of the `body` element.
* In the below code, `h1` element has two styles, one by `body` and other by `seperate class`. Then the `seperate class`/`seperate style` overrides  the `body` styling. So, `green` color style of `body` is overrided by `pink` color style of the `pink-text` class.
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
    </style>
    <body>
        <h1 class="pink-text">Hello World</h1>
    </body>
```

### CODE
[Click to view the code.](prioritize-one-style-over-another.html)

### OUTPUT
[Click to view the output.](http://htmlpreview.github.io/?https://github.com/saipothanjanjanam/freecodecamp-full-stack-dev/blob/master/Responsive_Web_Design_Certification/2.Basic_CSS/27.Prioritize_One_Style_Over_Another/prioritize-one-style-over-another.html)
