# Create A Form Element

### DESCRIPTION
* We can also create a forms in HTML.
* This forms can be submitted to server or any website.
* They are create by `form` element.
* It has several attributes.
* `action` attribute is used to submit the form to server or any website by its url as arguments.

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
        <input type="text" placeholder="cat photo URL">
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
    <form action="/submit-cat-photo">
        <input type="text" placeholder="cat photo URL">
    <form>
</main>
