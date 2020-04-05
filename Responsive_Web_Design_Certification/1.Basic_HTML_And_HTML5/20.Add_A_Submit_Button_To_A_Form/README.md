# Add A Submit Button To A Form

### DESCRIPTION
* We can also add button to HTML pages.
* Buttons can be added by the `button` element.
* `button` element has a `type` attribute if set to `submit` will submit all values to the form handler i.e `form` element.
* `action` attribute of `form` element decides to send the data or values by URL. 
* By clicking the button, the `action` attribute of the form takes action by sending the text written
  in the text field to the given URL.
```html
<form action="/go-to-website">
    <input type="text" placeholder="placeholder-we-need">
    <button type="submit"> Submit </button>
</form>
```

### CODE
```html
<h2>CatPhotoApp</h2>
<main>
    <p>Click here to view more <a href="#">cat photos</a>.</p>
    <a href="#"> <img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back.""></a>
    <p>Things cats love:<p>
    <ul>
        <li>cat nip</li>
        <li>laser pointers</li>
        <li>lasagna</li>
    </ul>
    <p>Top 3 things cats hate:<p>
    <ol>
        <li>flea treatment</li>
        <li>thunder</li>
        <li>other cats</li>
    </ol>
    <form action="submit-cat-photo">
        <input type="text" placeholder="cat photo URL">
        <button type="submit">Submit<button>
    </form>
</main>
```

### OUTPUT
<h2>CatPhotoApp</h2>
<main>
    <p>Click here to view more <a href="#">cat photos</a>.</p>
    <a href="#"> <img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back.""></a>
    <p>Things cats love:<p>
    <ul>
        <li>cat nip</li>
        <li>laser pointers</li>
        <li>lasagna</li>
    </ul>
    <p>Top 3 things cats hate:<p>
    <ol>
        <li>flea treatment</li>
        <li>thunder</li>
        <li>other cats</li>
    </ol>
    <form action="submit-cat-photo">
        <input type="text" placeholder="cat photo URL">
        <button type="submit">Submit</button>
    </form>
</main>