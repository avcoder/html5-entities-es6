# Usage

See https://www.npmjs.com/package/html5entitieses6
Can be used in modern browsers that use ES6 import.

```html
<body>
  <h1 id="h1"></h1>
  <script type="module">
    import { Html5Entities } from "https://www.unpkg.com/html5entitieses6";
    const entities = new Html5Entities();

    const msg = entities.decode("&#039;hello world&#39;");
    h1.textContent = msg;
    console.log(msg);
  </script>
</body>
```

# Credits:

Code is from https://www.npmjs.com/package/html-entities but instead of using `module.exports` to export the function, I changed it to `export function Html5Entities () {}`.
