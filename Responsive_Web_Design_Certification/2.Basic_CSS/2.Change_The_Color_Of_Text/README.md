# Change The Color Of Text

### DESCRIPTION
* We can change the color of the element's text using `color` style property of `style` attribute of that HTML element.
* It is good to end the properties with `;`.

### CODE
```html
<!DOCTYPE>
<html>
    <main>
        <h2 style="color:red;">CatPhotoApp</h2>
        <p>Click here to view more <a href="#">cat photos</a>.</p>
        <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."> </a>
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
                <input id="indoor" type="radio" value="indoor" name="indoor-outdoor" checked>Indoor
            </label>
            <label for="outdoor">
                <input id="outdoor" type="radio" value="outdoor" name="indoor-outdoor">Outdoor
            </label><br>
            <label for="loving">
                <input id="loving" type="checkbox" value="loving" name="personality" checked>Loving
            </label>
            <label for="lazy">
                <input id="lazy" type="checkbox" value="lazy" name="personality">Lazy
            </label>
            <label for="energetic">
                <input id="energetic" type="checkbox" value="energetic" name="personality">Energetic
            </label><br>
            <input type="text" nameholder="cat photo URL" required>
            <button type="submit">Submit</button>
        </form>
    </main>
</html>
```

### OUTPUT
<!DOCTYPE>
<html>
    <main>
        <h2 style="color:red;">CatPhotoApp</h2>
        <p>Click here to view more <a href="#">cat photos</a>.</p>
        <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."> </a>
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
                <input id="indoor" type="radio" value="indoor" name="indoor-outdoor" checked>Indoor
            </label>
            <label for="outdoor">
                <input id="outdoor" type="radio" value="outdoor" name="indoor-outdoor">Outdoor
            </label><br>
            <label for="loving">
                <input id="loving" type="checkbox" value="loving" name="personality" checked>Loving
            </label>
            <label for="lazy">
                <input id="lazy" type="checkbox" value="lazy" name="personality">Lazy
            </label>
            <label for="energetic">
                <input id="energetic" type="checkbox" value="energetic" name="personality">Energetic
            </label><br>
            <input type="text" nameholder="cat photo URL" required>
            <button type="submit">Submit</button>
        </form>
    </main>
</html>
