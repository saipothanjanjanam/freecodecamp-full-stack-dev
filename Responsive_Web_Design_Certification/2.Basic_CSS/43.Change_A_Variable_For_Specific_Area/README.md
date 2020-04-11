# Change A Variable For Specific Area

### DESCRIPTION
* Commonly the variables written in `root selector` is globally used in `all selectors` in the style sheet. But if we want to change the the `variable value` in `some selector` then, we redefine the `that variable` and assign the the `new value` and Now, the `new value` is used for styling for the part of document leaving the other part which uses the `root selector value`. 
```html
<style>
    :root {
        --some-variable: some-value;
    }
</style>
```

### CODE
[Click to view the code.](change-a-variable-for-a-specific-area.html)

### OUTPUT
[Click to view the output.](http://htmlpreview.github.io/?https://github.com/saipothanjanjanam/freecodecamp-full-stack-dev/blob/master/Responsive_Web_Design_Certification/2.Basic_CSS/43.Change_A_Variable_For_Specific_Area/change-a-variable-for-a-specific-area.html)
