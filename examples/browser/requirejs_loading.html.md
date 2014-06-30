---
layout: default
---

# Requirejs loading

Raw file: [requirejs_loading.html](requirejs_loading.html)

```html
<!DOCTYPE html>
<html>
<head>
  <title>math.js | require.js loading</title>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.11/require.min.js"></script>
</head>
<body>

<script>
  // load math.js using require.js
  require(['/js/lib/math.js'], function (math) {
    // evaluate some expression
    var result = math.eval('1.2 * (2 + 4.5)');
    document.write(result);
  });
</script>

</body>
</html>
```
