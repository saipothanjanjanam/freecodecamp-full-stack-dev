# Use A Custom CSS Variable 

### DESCRIPTION
* CSS `variables` is one of the way to to change many styles at once i.e we can use `variables` to change several elements styling at once.
* CSS `variable` is created by starting with `--` with the `name of the variable` you wish to give and assign it with value using `:`.
* `some-property` can be anything like `background`, `color`, `font-size`, etc, and the `some-value` can be any value depending upon type of `some-property`. To use that `variable` in some `class` as we assign that to `some-property` by `var(--some-variable)`.
```html
<style>
    .some-class{
        --some-variable: some-value;
    }
    .someother-class{
        some-property: var(--some-variable); 
    }
</style>
```

### CODE
[Click to view the code.](use-a-custom-css-variable.html)

### OUTPUT
[Click to view the output.](http://htmlpreview.github.io/?https://github.com/saipothanjanjanam/freecodecamp-full-stack-dev/blob/master/Responsive_Web_Design_Certification/2.Basic_CSS/39.Use_A_Custom_CSS_Variable/use-a-custom-css-variable.html)
