# Use A CSS Linear Gradient To Create A Stripped Element

### DESCRIPTION
* CSS provides the ability to use `color transitions`, otherwise known as gradients repeatedly one after another, on elements. This is accessed through the `background` property's `repeating-linear-gradient()` function.
* Below code applies repeating gradient in the direction given by `angle` and the colors of transition from color1 of given pixels(px) to color2 of given pixels(px) to and so .. on we need to. Here, color1 px starts and end with color2 px by transitioning, also next color starts at previous color end px starts new transition from there.
```html
<style>
	div{
		background: repeating-linear-gradient(gradient_direction, color1 px, color2 px, color3 px, ...);	
	}
</style>
```

### CODE
[Click to view the code.](create-a-gradual-css-linear-gradient.html)

### OUTPUT
[Click to view the output.](http://htmlpreview.github.io/?https://github.com/saipothanjanjanam/freecodecamp-full-stack-dev/blob/master/Responsive_Web_Design_Certification/3.Applied_Visual_Design/31.Create_A_Gradual_CSS_Linear_Gradient/create-a-gradual-css-linear-gradient.html)
