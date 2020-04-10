# Override All Other Styles By Using Important

### DESCRIPTION
* Commonly we use many CSS libraries to build the website, but sometimes those styles affect the original CSS styling written by us. We can override all other styling to the pa**rticular element using `important`. So the order of priority is as follows,
**Important** > **Inline Styling** > **ID Selector** > **Class Selector** > **Body Element Styling**
* In below example, all the styling applied to `h1` is overrided by `important` written in *pink-text* `class selector`.
```html
    <style>
        body {
            font-family: monospace;
            color:green;
            background-color:black;
        }
        .pink-text{
            color:pink !important;
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
[Click to view the code.](override-all-other-styles-by-using-important.html)

### OUTPUT
[Click to view the output.](http://htmlpreview.github.io/?https://github.com/saipothanjanjanam/freecodecamp-full-stack-dev/blob/master/Responsive_Web_Design_Certification/2.Basic_CSS/31.Override_All_Other_Styles_By_Using_Important/override-all-other-styles-by-using-important.html)
