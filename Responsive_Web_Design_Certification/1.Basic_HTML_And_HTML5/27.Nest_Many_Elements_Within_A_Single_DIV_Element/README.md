# Nest Many Elements Within A Single DIV Element

### DESCRIPTION
* `div` aka division element is the most general purpose container for other HTML5 elements.
* It is also the most commonly used element of all in the HTML5.
* `<div>` and `</div>` are opening and closing tags for `div` element.

### CODE
```html
<h2>CatPhotoApp</h2>
<main>
    <p>Click here to view more <a href="#">cat photos</a>.</p>
    <a href="#"> <img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>
    <div>
        <p>Things cat love:</p>
        <ul>
            <li>cat nip</li>
            <li>laser pointers</li>
            <li>lasagna</li>
        </ul>
        <p>Top 3 things cat hate:</p>
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
        <input type="text" placeholder="cat photo URL" required>
        <button type="submit">Submit</button>
    </form>
</main>
```

### OUTPUT

<h2>CatPhotoApp</h2>
<main>
    <p>Click here to view more <a href="#">cat photos</a>.</p>
    <a href="#"> <img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>
    <div>
        <p>Things cat love:</p>
        <ul>
            <li>cat nip</li>
            <li>laser pointers</li>
            <li>lasagna</li>
        </ul>
        <p>Top 3 things cat hate:</p>
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
        <input type="text" placeholder="cat photo URL" required>
        <button type="submit">Submit</button>
    </form>
</main>