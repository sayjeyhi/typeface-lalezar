Typeface package for byekan font

```bash
npm i -S typeface-lalezar
```
Fonts will be copied to node_modules/typeface-byekan/dist directory
and you could add them easily to your project :
```javascript
import 'typeface-lalezar';
```
and use `font-family: 'lalezarregular'` in your styling.


we used to do this with : 
```css
@font-face {
    font-family: 'lalezarregular';
    src: url('./dist/Lalezar-Regular-webfont.eot');
    src: url('./dist/Lalezar-Regular-webfont.eot?#iefix') format('embedded-opentype'),
    url('./dist/Lalezar-Regular-webfont.woff') format('woff'),
    url('./dist/Lalezar-Regular-webfont.ttf') format('truetype');
    font-weight: normal;
    font-style: normal;
}

```

### todo :
add `bold`,and `thin` fonts-faces
