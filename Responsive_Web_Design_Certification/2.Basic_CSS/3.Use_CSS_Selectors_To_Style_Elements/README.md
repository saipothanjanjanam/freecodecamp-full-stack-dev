# Use CSS Selectors To Style Elements

### DESCRIPTION
* First method to apply CSS styling is by inline CSS using `style` attribute i.e,
```html
<h2 style="color:red;">Some Text</h2>
```
* Second method to apply CSS by creating seperate `style` section and inside you can write a set of rules using css properties to style the HTML elements the way you want them to look. This piece of code changes all the `h2` elements text into `red`.
```html
<style>
    h2{
        color:red;
    }
</style>
```

### CODE
```html
<!DOCTYPE html>
<html>
    <style>
        h2 {
            color:blue;
        }
    </style>
    <h2>CatPhotoApp</h2>
    <main>
        <p>Click here to view more <a href="#">cat photos</a>.</p>
        <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>
        <div>
            <p>Things cats love:</p>
            <ul>
                <li>cat nip</li>
                <li>laser pointers</li>
                <li>lasagna</li>
            </ul>
            <p>Top 3 things cats hate:</p>
            <ul>
                <li>flea treatment</li>
                <li>thunder</li>
                <li>other cats</li>
            </ul>
        </div>
        <form action="/submit-cat-photo">
            <label for="indoor">
                <input id="indoor" value="indoor" type="radio" name="indoor-outdoor" checked>Indoor
            </label>
            <label for="outdoor">
                <input id="outdoor" value="outdoor" type="radio" name="indoor-outdoor">Outdoor
            </label><br>
            <label for="loving">
                <input id="loving" value="loving" type="checkbox" name="personality" checked>Loving
            </label>
            <label for="lazy">
                <input id="lazy" value="lazy" type="checkbox" name="personality">Lazy
            </label>
            <label for="energetic">
                <input id="energetic" value="energetic"type="checkbox" name="personality">Energetic
            </label><br>
            <input type="text" nameholder="cat photo URL" required>
            <button type="submit">Submit</button>
        </form>
    </main>
</html>
```

### OUTPUT 
[Click to view the output.](use-css-selectors-to-style-elements.html)
