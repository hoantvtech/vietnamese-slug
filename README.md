## Vietnamese Slug
- Package hỗ trợ chuyển đổi từ tiếng Việt có dấu sang dạng không dấu, hỗ trợ SEO, URL thân thiện, hỗ trợ chuyển đổi tên file sang định dạng thaan thiện.
## Documentation
### Example
```javascript
const { toVietnameseSlug } = require("vietnamese-url");
const input = "Tiêu đề này được viết bằng tiếng    Việt   ";
const output = toVietnameseSlug(input);
console.log(output);
// tieu-de-nay-duoc-viet-bang-tieng-viet
```
### Custom slug character
```sh
const { toVietnameseSlug } = require("vietnamese-url");
const input = "Tiêu đề này được viết bằng tiếng    Việt   ";
const output = toVietnameseSlug(input, "*");
console.log(output);
// tieu*de*nay*duoc*viet*bang*tieng*viet
```

### ES6
```javascript
import { toVietnameseSlug } from "vietnamese-url";
const slug = toVietnameseSlug("Tiêu đề này được viết bằng tiếng    Việt   ");
console.log("slug: ", slug);
// tieu-de-nay-duoc-viet-bang-tieng-viet
```

### ToSlugFile
```javascript
const { toSlugFile } = require("vietnamese-url");
const slug = toSlugFile("Đường dẫn ảnh viết bằng tiếng    Việt   .jpg");
console.log("slug: ", slug);
// duong-dan-anh-viet-bang-tieng-viet-dr1kz.jpg
```
```javascript
import { toSlugFile } from "vietnamese-url";
const slug = toSlugFile("Đường dẫn ảnh viết bằng tiếng    Việt   .jpg");
console.log("slug: ", slug);
// duong-dan-anh-viet-bang-tieng-viet-dr1kz.jpg
```