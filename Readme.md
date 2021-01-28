# Snowpack reproducible test case


This repo illustrates issue in snowpack which seems to ignore local modules named same built-in modules in node producing errors like:

```
Module "buffer" (Node.js built-in) is not available in the browser. Run Snowpack with --polyfill-node to fix.
```

