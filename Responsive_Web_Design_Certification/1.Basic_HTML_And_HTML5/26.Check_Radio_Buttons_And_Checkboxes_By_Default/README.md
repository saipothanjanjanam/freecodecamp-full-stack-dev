# Check Radio Buttons And Checkboxes By Default

### DESCRIPTION

* Commonly, sometimes its good to enable some of the options by default.
* So, to enable radio buttons and checkboxes by default we use `checked` flag in `input` attribute.
```html
<label for="some-id">
    <input id="some-id" type="radio" value="some-option" name="some-name">some-option
</label>
```

### CODE
```html
<h2>CatPhotoApp</h2>
<main>
    <p>Click here to view more <a href="#">cat photos</a>.</p>
    <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>
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
    <form action="/submit-cat-photo">
        <label for="indoor">
            <input id="indoor" type="radio" value="indoor" name="indoor-outdoor" checked>Indoor
        </label>
        <label for="outdoor">
            <input id="outdoor" type="radio" value="outdoor" name="indoor-outdoor">Outdoor
        </label><br>
        <label for="strong">
            <input id="strong" type="checkbox" value="strong" name="personality" checked>Strong
        </label>
        <label for="weak">
            <input id="weak" type="checkbox" value="weak" name="personality">Weak
        </label>
        <label for="active">
            <input id="active" type="checkbox" value="active" name="personality">Active
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
    <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>
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
    <form action="/submit-cat-photo">
        <label for="indoor">
            <input id="indoor" type="radio" value="indoor" name="indoor-outdoor" checked>Indoor
        </label>
        <label for="outdoor">
            <input id="outdoor" type="radio" value="outdoor" name="indoor-outdoor">Outdoor
        </label><br>
        <label for="strong">
            <input id="strong" type="checkbox" value="strong" name="personality" checked>Strong
        </label>
        <label for="weak">
            <input id="weak" type="checkbox" value="weak" name="personality">Weak
        </label>
        <label for="active">
            <input id="active" type="checkbox" value="active" name="personality">Active
        </label><br>
        <input type="text" placeholder="cat photo URL" required>
        <button type="submit">Submit</button>
    </form>
</main>

