<h1>aquarello.js</h1>

<b>A simple javascript and CSS and JS framework with a new color palette for the web. Easy to install, easy to use, beautiful to watch. Checkout [Aquarello WebSite](http://lorenzoferrante.github.io/aquarello/)!</b>

<h2>How to use</h2>
------------------------

For use it download or clone the repo and just put the link to the CSS file before the closing </body> tag of your html page.

```
<link rel="stylesheet" type="text/css" href="aquarello.css">
<link rel="stylesheet" type="text/css" href="aquarello.min.css"> // minified version
```

Now you have two methods to choose the color you want from the color palette. The first is through CSS. In your HTML add to an element the color's class you want. For example:

`<p id="..." class="mandarine"> ... </p>`

To add a backgrund-color instead of font color, just add `-Bg` at the end of the color's class. For example:

`<div class="mandarine-Bg"> ... </div>`

The second method is using javascript. Maybe you will need jQuery so grab the latest release [here](http://code.jquery.com/jquery-latest.min.js). When you've done this, just write a script before the closing `</body>` tag, like this:

```
$('your-element').addClass('mandarine');
$('your-element').addClass('mandarine-Bg'); // background-color
```
<h2>Thanks</h2>

Making the web site I found inspiration in @daneden 's website [Animate.css](http://daneden.github.io/animate.css/), and I also used his great CSS tools to add animation to my web site.
