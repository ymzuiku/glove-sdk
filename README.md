# glove-sdk

glove-sdk is [Glove testing sdk](https://glove.gewulian.com/) modules.

## Start

### Use npm

```sh
npm i glove-sdk
# or
pnpm i glove-sdk
# or
yarn add glove-sdk
```

In your project import the `glove-sdk`

```js
import "glove-sdk";
// OK, It's done
```

### Or add `<script></script>` in your `html`

```html
<script>
  (function (w, d) {
    var s = d.createElement("script");
    s.src = "https://glove.gewulian.com/sdk.js";
    s.async = true;
    (d.head || d.body).appendChild(s);
  })(window, document);
  // OK, It's done
</script>
```

More details view: [Glove Website](https://glove.gewulian.com/)
