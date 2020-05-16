<p align="center">
    <img src="https://user-images.githubusercontent.com/6702424/80216211-00ef5280-863e-11ea-81de-59f3a3d4b8e4.png">  
</p>
<p align="center">
    <i>A cool module that does things</i>
    <br>
    <br>
    <img src="https://github.com/cahuzacf/automatic-octo-bassoon/workflows/ci/badge.svg">
    <img src="https://img.shields.io/bundlephobia/minzip/automatic-octo-bassoon">
    <img src="https://img.shields.io/npm/dw/automatic-octo-bassoon">
</p>
<p align="center">
  <a href="https://github.com/cahuzacf/automatic-octo-bassoon">Home</a>
  -
  <a href="https://github.com/cahuzacf/automatic-octo-bassoon">Documentation</a>
  -
  <a href="https://gitter.im/automatic-octo-bassoon/">Chat</a>
</p>

---

# Install / Import

```bash
> npm install --save automatic-octo-bassoon
```
```typescript
import { myFunction, myObject } from 'automatic-octo-bassoon'; 
```

Specific import

```typescript
import { myFunction } from 'automatic-octo-bassoon/myFunction'
import { myObject } from 'automatic-octo-bassoon/myObject'
```

## From HTML with CDN

Expose a global ( wider browser support):  

```html
<script src="//unpkg.com/automatic-octo-bassoon/umd_bundle.min.js"></script>
<script>
  var myFunction = automatic_octo_bassoon.myFunction;
</script>
```

Or import as an ES module:  

```html
<script type="module">
  import { myFunction, myObject } from '//unpkg.com/automatic-octo-bassoon/zz_esm/index.js';
</script>
```

## Contribute

```bash
npm install
npm run build
npm test
```
change 1

change 2
