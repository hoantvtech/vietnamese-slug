## Vietnamese Slug
- Package to convert Vietnamese string to slug.
## Documentation
### Example
```javascript
const toSlug = require("vietnamese-url");
const input = "Tiêu đề này được viết bằng tiếng    Việt   ";
const output = toSlug(input);
console.log(output);
// tieu-de-nay-duoc-viet-bang-tieng-viet
```
### Custom slug character
```sh
const toSlug = require("vietnamese-url");
const input = "Tiêu đề này được viết bằng tiếng    Việt   ";
const output = toSlug(input, "*");
console.log(output);
// tieu*de*nay*duoc*viet*bang*tieng*viet
```