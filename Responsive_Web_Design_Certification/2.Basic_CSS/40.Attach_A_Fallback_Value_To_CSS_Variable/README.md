# Attach A Fallback Value To A CSS Variable 

### DESCRIPTION
* Some Browsers can't show all the colors or some values or if CSS `variables` are not set, So we always attach a fallback value to some important CSS variables to avoid default action by browser.
* `some-property` can be anything like `background`, `color`, `font-size`, etc, and the `some-value` can be any value depending upon type of `some-property`. To use that `variable` and `fallback value` in some `class` as we assign that to `some-property` by `var(--some-variable, some-fallback-value)`.
```html
<style>
    .some-class{
        --some-variable: some-value;
    }
    .someother-class{
        some-property: var(--some-variable, some-fallback-value); 
    }
</style>
```

### CODE
[Click to view the code.](attach-a-fallback-value-to-a-css-variable.html)

### OUTPUT
[Click to view the output.](http://htmlpreview.github.io/?https://github.com/saipothanjanjanam/freecodecamp-full-stack-dev/blob/master/Responsive_Web_Design_Certification/2.Basic_CSS/40.Attach_A_Fallback_Value_To_CSS_Variable/attach-a-fallback-value-to-a-css-variable.html)
