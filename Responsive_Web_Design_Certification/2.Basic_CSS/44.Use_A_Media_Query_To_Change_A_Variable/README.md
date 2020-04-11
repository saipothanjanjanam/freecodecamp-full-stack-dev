# Use A Media Query To Change A Variable

### DESCRIPTION
* CSS Variables can simplify the way you use media queries.
* For instance, when your screen is smaller or larger than your media query break point, you can change the value of a variable, and it will apply its style wherever it is used. 
* Here, the if the screen width is more than `350px` then the `variable values` in the `root` are used. As the screen size decreases, then  `variable values` in the `@media` are used. So, these CSS Variables simplify the media queries
```html
    <style>
        :root {
        --penguin-size: 300px;
        --penguin-skin: gray;
        }
        @media (max-width: 350px) {
        :root {
            /* Only change code below this line */
            --penguin-size: 200px;
            --penguin-skin: black;
            /* Only change code above this line */
        }
        }
    </style>
```

### CODE
[Click to view the code.](use-a-media-query-to-change-a-variable.html)

### OUTPUT
[Click to view the output.](http://htmlpreview.github.io/?https://github.com/saipothanjanjanam/freecodecamp-full-stack-dev/blob/master/Responsive_Web_Design_Certification/2.Basic_CSS/44.Use_A_Media_Query_To_Change_A_Variable/use-a-media-query-to-change-a-variable.html)
