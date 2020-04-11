# Inherit CSS Variables

### DESCRIPTION
* Commonly, the `variables` written in one `class selector` can only be used within that `selector` only. Also, the particular `selectors` that can access the `variables` of `other selectors` if they are related by the principle of `inheritance`. So, commonly the `variables` that are written in `root` can be globally accessed elsewhere in the overall styling sheet for making use of `inheritance`. `root` is also called as `pseudo class selector` which directly links with `html tag` of that particular document for using `inheritance`.
* We define `root class selector` below as follows. Now, `some-variable` can be used in any other `selector`. 
```html
<style>
    :root {
        --some-variable: some-value;
    }
</style>
```

### CODE
[Click to view the code.](inherit-css-variables.html)

### OUTPUT
[Click to view the output.](http://htmlpreview.github.io/?https://github.com/saipothanjanjanam/freecodecamp-full-stack-dev/blob/master/Responsive_Web_Design_Certification/2.Basic_CSS/42.Inherit_CSS_Variables/inherit-css-variables.html)
