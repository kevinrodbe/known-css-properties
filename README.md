# CSS properties

List of standard and browser specific CSS properties.

## Source

1. Standard properties (only states): http://www.w3.org/Style/CSS/all-properties.en.json) 
2. Browser supported properties from `window.getComputedStyle` / `document.body.style`):

 ### Windows
   |                   | XP     | 7      | 8      | 10     | 
   | ----------------- | ------ | ------ | ------ | ------ | 
   | Chrome            | 14-49  | 14-50  | 22-50  | 37-50  | 
   | Firefox           | 6-45   | 6-45   | 39-45  | 32-45  | 
   | Internet Explorer |        | 10-11  | 10-11  | 11     | 
   | Edge              |        |        |        | 13     | 

 ### Others:

 - Safari: 6, 6.2, 7, 8, 9.1
 - Mobile Safari: 6, 7, 8, 8.3, 9.0, 9.3
 - Chrome Android: 30, 37 
 - Opera Win XP 12.10, 12.14, 12.15, 12.16 

### JavaScript API

```js
const properties = require('known-css-properties').all;
```