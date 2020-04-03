# Use HTML To Require A Field

### DESCRIPTION
* We can make HTML5 to make sure that input field is required i.e user can not submit the `form` unless he write the required field.
* When user click submit button with that required field empty, then user will get a prompt to fill that required field.
* It can be achieved by the keyword attribute `required` in `input` element.
```html
<input type="text" placeholder="some-placeholder" required>
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
    <form action="/submit-cat-photo">
        <input type="text" placeholder="cat photo URL" required>
        <button type="submit">Submit</button>
    </form>
</main>
```

### OUTPUT
<h2>CatPhotoApp</h2>
<main>
    <p>Click here to view more <a href="#">cat photos</a>.</p>
    <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt=""></a>
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
    <form action="/submit-cat-photo">
        <input type="text" placeholder="cat photo URL" required>
        <button type="submit">Submit</button>
    </form>
</main>