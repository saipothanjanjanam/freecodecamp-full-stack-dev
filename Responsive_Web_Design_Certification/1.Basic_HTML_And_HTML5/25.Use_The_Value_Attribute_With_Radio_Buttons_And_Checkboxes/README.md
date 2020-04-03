# Use The Value Attribute With Radio Buttons and Checkboxes

### DESCRIPTION
* Commonly after clicking the `submit` button, the `action` attribute of the form takes action by sending the data filled in the form to server or other destination.
* But, the data typed in the radio buttons or checkboxes is not sent the data rather they are sent as `yes` or `no` which is quite not useful.
* So, in such case to send the options as value we use `value` attribute of the input and we initialise to `value` of the `option`. 
```html
<label for="some-id">
    <input id="some-id" type="checkbox" value="some-option" name="some-name">some-option
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
            <input id="indoor" type="radio" value="indoor" name="indoor-outdoor">Indoor
        </label>
        <label for="outdoor">
            <input id="outdoor" type="radio" value="outdoor" name="indoor-outdoor">Outdoor
        </label><br>
        <label for="strong">
            <input id="strong" type="checkbox" value="strong" name="personality">Strong
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
            <input id="indoor" type="radio" value="indoor" name="indoor-outdoor">Indoor
        </label>
        <label for="outdoor">
            <input id="outdoor" type="radio" value="outdoor" name="indoor-outdoor">Outdoor
        </label><br>
        <label for="strong">
            <input id="strong" type="checkbox" value="strong" name="personality">Strong
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
