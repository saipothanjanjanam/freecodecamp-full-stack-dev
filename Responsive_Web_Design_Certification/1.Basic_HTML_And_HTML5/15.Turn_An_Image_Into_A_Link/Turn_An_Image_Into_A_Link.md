# Turn An Image Into A Link

### DESCRIPTION
* We can also make a image into a link.
* We just have to nest the `img` element inside of `a`(anchor) element in order to do that.
* The `href` attribute in the `a` tag will be the web address we go to when we press the image.
```html
<a href="webpage we need to go after clicking the photo"><img src="image-path/url"></a>
```

### CODE 
```html
<h2>CatPhotoApp</h2>
<main>
    <p>Click here to view more <a href="#">cat photos.</a></p>
    <a href="#"> <img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>
    <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
    <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
</main>
```

### OUTPUT
<h2>CatPhotoApp</h2>
<main>
    <p>Click here to view more <a href="#">cat photos.</a></p>
    <a href="#"> <img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>
    <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
    <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
</main>