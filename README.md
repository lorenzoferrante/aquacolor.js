## Aquarello

<b>A simple javascript and CSS and JS framework with a new color palette for the web. Easy to install, easy to use, beautiful to watch.</b>

For use it download or clone the repo and just put the link to the CSS file before the closing </body> tag of your html page.

`<link rel="stylesheet" type="text/css" href="aquarello.css">`

And now just write this in your own script:

```javascript
speak('en', 'Hello World!'); 
```
==================================

### How it works

```javascript
speak(language, text-To-Read); 
```

#### Example:
You can find a working example of the framework here: [JSFiddle](http://jsfiddle.net/F5fNw/)
```html
<script type="text/javascript" src="simpleSpeak.js">
<script>
speak('en', 'Yup, this is great!'); // The browser will speak 'Yup, this is great!'
</script>
```

The `speak()` function has 2 necessary parameters. The first is for the language you need to, while the second is for the text you need the browser speaks. Both parameters are strings.

simpleSpeak.js is available in all the languages. Below there are English, Italian, German and French codes to write in the first parameter. At the end I linked Google Page web site where are all the language codes. So, to change the spoken language, just write in the first parameter the code you want.

* English = `en` <br/>
* Italian = `it` <br/>
* German = `de`  <br/>
* French = `fr`  <br/>

[All Google language codes](https://sites.google.com/site/tomihasa/google-language-codes)

=========================

### Limitation

This framework has got just a limitation. It can read til 100 characters because it uses Google Translate service. I'm working on it to fix that limitation. Stay tuned for updates!

P.S. Don't worry! 100 characters are enought for the moment!
```javascript
// 100 Characters
'AAAAAAAAAA BBBBBBBBBB CCCCCCCCCC DDDDDDDDDD EEEEEEEEEE FFFFFFFFFF GGGGGGGGGG HHHHHHHHHH IIIIIIIIIII' 
```

