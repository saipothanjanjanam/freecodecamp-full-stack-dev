# Create A Set Of Radio Buttons

### DESCRIPTION
* We can also create radio buttons using HTML5.
* They can be created changing `type` attribute to `radio` in the `input` element.
* Commonly, we nest the each `input` element in each `label` element.
```html
<label>
    <input id="some-id" type="radio" name="some-name">some-option.
</label>
```
* We can also create multiple radio buttons for the single query/question.
* Multiple radio buttons will have the same `name` attribute, so that if one of them is selected, others will be unselected automatically.
* Commonly, its nice practice to use `for` attribute in the `label` element. This will be helpful for developers and help us to differentiate code easily.
* We commonly give name to `for` attribute the `id` of that particular `radio` button.
```html
<label for="some-id">
    <input id="some-id" type="radio" name="some-name">some-option.
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
    <ol>
        <li>flea treatment</li>
        <li>thunder</li>
        <li>other cats</li>
    </ol>
    <form action="/cat-photo-submit">
        <input type="text" nameholder="cat photo URL" required>
        <button type="submit">Submit</button><br>
        <label for="indoor">
            <input id="indoor" type="radio" name="indoor-outdoor">indoor
        </label>
        <label for="outdoor">
            <input id="outdoor" type="radio" name="indoor-outdoor">outdoor
        </label>
    <form>
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
    <ol>
        <li>flea treatment</li>
        <li>thunder</li>
        <li>other cats</li>
    </ol>
    <form action="/cat-photo-submit">
        <input type="text" nameholder="cat photo URL" required>
        <button type="submit">Submit</button><br>
        <label for="indoor">
            <input id="indoor" type="radio" name="indoor-outdoor">indoor
        </label>
        <label for="outdoor">
            <input id="outdoor" type="radio" name="indoor-outdoor">outdoor
        </label>
    <form>
</main>
