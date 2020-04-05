# Create A Set Of Checkboxes 

### DESCRIPTION
* We can also create checkbox buttons using HTML5.
* They can be created changing `type` attribute to `checkbox` in the `input` element.
* Commonly, we nest the each `input` element in each `label` element.
```html
<label>
    <input id="some-id" type="checkbox" name="some-name">some-option.
</label>
```
* We can also create multiple checkboxes for the single query/question.
* Multiple checkboxes will have the same `name` attribute, so that if one of them is selected, others will be unselected automatically.
* Commonly, its nice practice to use `for` attribute in the `label` element. This will be helpful for developers and help us to differentiate code easily.
* We commonly give name to `for` attribute the `id` of that particular `checkbox` button.
```html
<label for="some-id">
    <input id="some-id" type="checkbox" name="some-name">some-option.
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
            <input id="indoor" type="radio" name="indoor-outdoor">Indoor
        </label>
        <label for="outdoor">
            <input id="outdoor" type="radio" name="indoor-outdoor">Outdoor
        </label><br>
        <label for="strong">
            <input id="strong" type="checkbox" name="personality">Strong
        </label>
        <label for="weak">
            <input id="weak" type="checkbox" name="personality">Weak
        </label>
        <label for="active">
            <input id="active" type="checkbox" name="personality">Active
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
            <input id="indoor" type="radio" name="indoor-outdoor">Indoor
        </label>
        <label for="outdoor">
            <input id="outdoor" type="radio" name="indoor-outdoor">Outdoor
        </label><br>
        <label for="strong">
            <input id="strong" type="checkbox" name="personality">Strong
        </label>
        <label for="weak">
            <input id="weak" type="checkbox" name="personality">Weak
        </label>
        <label for="active">
            <input id="active" type="checkbox" name="personality">Active
        </label><br>
        <input type="text" placeholder="cat photo URL" required>
        <button type="submit">Submit</button>
    </form>
</main>
