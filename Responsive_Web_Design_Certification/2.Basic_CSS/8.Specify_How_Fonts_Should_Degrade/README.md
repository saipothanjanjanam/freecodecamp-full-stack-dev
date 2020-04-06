# Specify How Fonts Should Degrade

### DESCRIPTION

* We can also degrade fonts for HTML elements in the document using CSS property `font-family` i.e if we don't find our first preference font then, second preference font will be applied to HTML elements. Here, in the example below if we document didn't find `Lobster` font or it is not installed then it is replaced by `Helevetica` the immediate next font for the `h2` element.
```html
<style>
    h2 {
        font-family: Lobster, Helevetica;
    }
</style>
```

### CODE
[Click to view the code.](specify-how-fonts-should-degrade.html)

### OUTPUT
[Click to view the output.](http://htmlpreview.github.io/?https://github.com/saipothanjanjanam/freecodecamp-full-stack-dev/blob/master/Responsive_Web_Design_Certification/2.Basic_CSS/8.Specify_How_Fonts_Should_Degrade/specify-how-fonts-should-degrade.html)

