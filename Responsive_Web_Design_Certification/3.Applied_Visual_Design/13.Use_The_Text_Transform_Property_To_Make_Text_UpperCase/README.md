# Use The Text Transform Property To Make Text UpperCase

### DESCRIPTION
* We can change the case of the text of an element using CSS property `text-transform`.
* It allows consistency in the text of the web page and helps us by not changing the text in the html element by hand.
* CSS property `text-transform` can have different values and if we apply to text `transform me` then those are as follows,
    * `uppercase`  -  "TRANSFORM ME"
    * `lowercase`  -  "transform me"
    * `capitalize` -  "Transform Me"
    * `initial`    -  Use the default value
    * `inherit`    -  Use the text-transform value from the parent element
    * `none`	   -  Default: Use the original text
* Below code changes the text of element using `some-class` to `uppercase`.
```html
    <style>
    .some-class{
        text-transform: uppercase;
    }
    </style>
```

### CODE
[Click to view the code.](use-the-text-transform-property-to-make-text-uppercase.html)

### OUTPUT
[Click to view the output.](http://htmlpreview.github.io/?https://github.com/saipothanjanjanam/freecodecamp-full-stack-dev/blob/master/Responsive_Web_Design_Certification/3.Applied_Visual_Design/13.Use_The_Text_Transform_Property_To_Make_Text_UpperCase/use-the-text-transform-property-to-make-text-uppercase.html)