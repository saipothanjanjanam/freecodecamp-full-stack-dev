# Lock An Element To Its Parent With Absolute Positioning

### DESCRIPTION
* Another type of positioning in webpage is using `absolute` positioning.
* This `absolute` positioning removes the elements from normal flow, surrounding items are ignored and make it relative to its nearest ancestor elements which uses `relative` or the to its parent `container`.
* If the nearest ancestor element is not found, then it will become relative to default `body` element of the webpage.
* We can still use `left`, `right`, etc for setting its position in `px(pixels)`.
* Below example applies `absolute` positioning to the element.
```html
<style>
    some-element{
        position: absolute; 
        <!-- Opposite to the side you want to push -->
        top: 10px; <!-- Bottom push -> so top -->
        left: 5px; <!-- Right push -> so left -->
    }
</style>
```

### CODE
[Click to view the code.](lock-an-element-to-its-parent-with-absolute-positioning.html)

### OUTPUT
[Click to view the output.](http://htmlpreview.github.io/?https://github.com/saipothanjanjanam/freecodecamp-full-stack-dev/blob/master/Responsive_Web_Design_Certification/3.Applied_Visual_Design/21.Lock_An_Element_To_Its_Parent_With_Absolute_Positioning/lock-an-element-to-its-parent-with-absolute-positioning.html)
