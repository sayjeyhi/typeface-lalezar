# Easy to use lalezarregular typeface

> 😄 use me with npm install

Typeface package for lalezarregular font with [typography.js](https://github.com/KyleAMathews/typography.js)

```bash
npm i -S typeface-lalezarregular
```
Fonts will be copied to node_modules/typeface-lalezarregular/dist directory
and you could add them easily to your project :
```javascript
import 'typeface-lalezarregular';
```
and use `font-family: 'Lalezar-Regular'` in your styling.


we used to do this with : 
```css
/* font converted using font-converter.net. thank you! */
@font-face {
    font-family: "Lalezar-Regular";
    src: url("./dist/Lalezar-Regular.eot"); /* IE9 Compat Modes */
    src: url("./dist/Lalezar-Regular.eot?#iefix") format("embedded-opentype"), /* IE6-IE8 */
    url("./dist/Lalezar-Regular.otf") format("opentype"), /* Open Type Font */
    url("./dist/Lalezar-Regular.svg") format("svg"), /* Legacy iOS */
    url("./dist/Lalezar-Regular.ttf") format("truetype"), /* Safari, Android, iOS */
    url("./dist/Lalezar-Regular.woff") format("woff"), /* Modern Browsers */
    url("./dist/Lalezar-Regular.woff2") format("woff2"); /* Modern Browsers */
    font-weight: normal;
    font-style: normal;
}

```

### todo :
add `bold`,and `thin` fonts-faces
