<h1 align="center"><code>check-absolute-url.js</code></h1>

<p align="center">Validate absolute URLs in strings and arrays</p>

## ⚙️ Installation

```js
npm i check-absolute-url
```

**CDN Links:**
- https://cdn.jsdelivr.net/npm/check-absolute-url@1.0.0/check-absolute-url.js
- https://www.unpkg.com/check-absolute-url@1.0.0/check-absolute-url.js

## 📖 Usage

#### ▪ Import

```js
// ES6
import checkAbsoluteUrl from "check-absolute-url";

// commonjs
const checkAbsoluteUrl = require("check-absolute-url");
```

#### ▪ Check with string

```js
const checked = checkAbsoluteUrl('https://www.example.com/path');

console.log(checked); // True
```

#### ▪ Check with array

```js
const urls = [
    'http://localhost:3000',
    'ftp://ftp.example.com/file.zip',
    '/path',
    'example.com',
    'C:\\path\\to\\file.txt'
];

const checked = checkAbsoluteUrl(urls);

console.log(checked); // [true, true, false, false, false]
```

---

[Support me on Patreon](https://www.patreon.com/axorax) — 
[Check out my socials](https://github.com/axorax/socials)