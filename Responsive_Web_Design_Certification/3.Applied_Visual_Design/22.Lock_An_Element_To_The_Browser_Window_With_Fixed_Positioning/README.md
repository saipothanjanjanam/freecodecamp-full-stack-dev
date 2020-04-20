# Lock An Element To The Browser With Fixed Positioning

### DESCRIPTION
* Another type of positioning in webpage is using `fixed` positioning.
* This `fixed` positioning removes the elements from normal flow, similar to the `absolute` positioning but `major difference` is that it the element will be fixed to the browser and visible even when we are scrolling down. So, this property can be useful for `navigation bar` or `contents bar` on the left
* We can still use `left`, `right`, etc for setting its position in `px(pixels)`.
* Below example applies `fixed` positioning to the element.
```html
<style>
    some-element{
        position: fixed; 
        <!-- Opposite to the side you want to push -->
        top: 10px; <!-- Bottom push -> so top -->
        left: 5px; <!-- Right push -> so left -->
    }
</style>
```

### CODE
[Click to view the code.](lock-an-element-to-the-browser-window-with-fixed-positioning.html)

### OUTPUT
[Click to view the output.](http://htmlpreview.github.io/?https://github.com/saipothanjanjanam/freecodecamp-full-stack-dev/blob/master/Responsive_Web_Design_Certification/3.Applied_Visual_Design/22.Lock_An_Element_To_The_Browser_Window_With_Fixed_Positioning/lock-an-element-to-the-browser-window-with-fixed-positioning.html)
