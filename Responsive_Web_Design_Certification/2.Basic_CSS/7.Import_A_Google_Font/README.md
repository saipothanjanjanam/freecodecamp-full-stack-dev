# Import A Google Font

### DESCRIPTION

* There are many fonts in the operating system, but if you want to use external fonts like from online, then you can easily use them in HTML using CSS. For external and online Fonts, developers most oftely use `google fonts API`. Go to `Google Fonts` and select the font you are interested and then copy the url of the font. Now to use the font, you have to simple write a small code snippet as of below at above the `main` tag of HTML document.
```html
<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">
```
 
 * Now we can use that font by css property `font-family` by `font-family: FAMILY_NAME, "GENERIC_NAME"`  applies the GENERIC_NAME font of FAMILY_NAME font family to the HTML element i.e in this example `"Open Sans"` of `Lobster` font family to `p` element.
 ```html
 <style>
    p {
        font-family: Lobster, "Open Sans";
    }
</style>
 ```

### CODE
[Click to view the code.](import-a-google-font.html)

### OUTPUT
[Click to view the output.](http://htmlpreview.github.io/?https://github.com/saipothanjanjanam/freecodecamp-full-stack-dev/blob/master/Responsive_Web_Design_Certification/2.Basic_CSS/7.Import_A_Google_Font/import-a-google-font.html)

