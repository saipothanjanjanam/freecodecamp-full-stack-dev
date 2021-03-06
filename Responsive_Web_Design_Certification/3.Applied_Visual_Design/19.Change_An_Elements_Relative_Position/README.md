# Change An Elements Relative Position

### DESCRIPTION
* There are two types of elements in HTML, 
    * one is box-type elements(`p`, `h`, `a`, `div`) which uses CSS box model and are like a rectangle.
    * second is inline-elements(`img`, `span`).
* So, when we use box elements they are positioned in the webpage normally and also know as normal flow.
* There another type of setting position to these elements i.e., `relative` means they are positioned relative to its `normal` position. We can also use CSS properties like `top`, `bottom`, `left`, `right` so that we can adjust the position of these elements relatively with respect to the normal position. 
* Positioning gives you a lot of flexibility and power over the visual layout of a page. It's good to remember that no matter the position of elements, the underlying HTML markup should be organized and make sense when read from top to bottom. This is how users with visual impairments (who rely on assistive devices like screen readers) access your content.
* Below code shows how to implement relative position for an element which uses`some-class` selector and pushes the element bottom by `10px`.
```html
<style>
    some-element{
        position: relative; 
        top: 10px;
    }
</style>
```

### CODE
[Click to view the code.](change-an-elements-relative-position.html)

### OUTPUT
[Click to view the output.](http://htmlpreview.github.io/?https://github.com/saipothanjanjanam/freecodecamp-full-stack-dev/blob/master/Responsive_Web_Design_Certification/3.Applied_Visual_Design/19.Change_An_Elements_Relative_Position/change-an-elements-relative-position.html)