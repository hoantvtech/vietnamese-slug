## Vietnamese Slug
- Package to convert Vietnamese string to slug.
## Documentation
```sh
$ npm install vietnamese-url --save
```
```sh
$ toVietnameseSlug(string)
```
### Custom slug character
```sh
$ toVietnameseSlug(string, character)
```
### Example
```javascript
const toSlug = require("vietnamese-url");
const input = "Tiêu đề này được viết bằng tiếng    Việt   ";
const output = toSlug(input);
console.log(output);
// tieu-de-nay-duoc-viet-bang-tieng-viet
```