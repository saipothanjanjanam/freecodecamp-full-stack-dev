# Define The Head And Body Of An HTML Document

### DESCRIPTION
* Besides the elements like `a`, `img`, `form`, etc,.. there are some elements which are included in every `HTML` document.
* These are `head` and `body` elements which are other level elements for organising the overall structure of the `HTML` document.
* These are enclosed within the `html` tags.
* Commonly,
    * `head` element contains all the metacontent i.e `link`, `title`, `meta`, `style`, etc,.. 
    * `body` element contains the overall page content that is to be showed on the web browser.  
```html
<!DOCTYPE html>
<html>
    <head>
        <!-- All meta elements goes here -->
    </head>
    <body>
        <!-- All the content of the page goes here -->
    </body>
</html>
``` 

### CODE
```html
<!DOCTYPE html>
<html>
    <head>
        <!-- All meta elements goes here -->
        <title>The best page ever<title>
    </head>
    <body>
        <!-- All the content of the page goes here -->
        <h1>The best page ever</h1>
        <p>Cat ipsum dolor sit amet, jump launch to pounce upon little yarn mouse, bare fangs at toy run hide in litter box until treats are fed. Go into a room to decide you didn't want to be in there anyway. I like big cats and i can not lie kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff. Meow i could pee on this if i had the energy for slap owner's face at 5am until human fills food dish yet scamper. Knock dish off table head butt cant eat out of my own dish scratch the furniture. Make meme, make cute face. Sleep in the bathroom sink chase laser but pee in the shoe. Paw at your fat belly licks your face and eat grass, throw it back up kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
    </body>
</html>
``` 

### OUTPUT
<!DOCTYPE html>
<html>
    <head>
        <!-- All meta elements goes here -->
        <!-- <title>The best page ever<title>  --> <!-- This line is commented to compile in Markdown Document-->
    </head>
    <body>
        <!-- All the content of the page goes here -->
        <h1>The best page ever</h1>
        <p>Cat ipsum dolor sit amet, jump launch to pounce upon little yarn mouse, bare fangs at toy run hide in litter box until treats are fed. Go into a room to decide you didn't want to be in there anyway. I like big cats and i can not lie kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff. Meow i could pee on this if i had the energy for slap owner's face at 5am until human fills food dish yet scamper. Knock dish off table head butt cant eat out of my own dish scratch the furniture. Make meme, make cute face. Sleep in the bathroom sink chase laser but pee in the shoe. Paw at your fat belly licks your face and eat grass, throw it back up kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
    </body>
</html>