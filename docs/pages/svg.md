---
title: SVG Favicon Test
description: Test whether your browser supports favicon in SVG format
lang-ref: svg
---

Currently both Chrome and Firefox support favicons in the SVG format, SVG will get smaller file size and better displays.

If you can see the yellow SVG icon appear in your browser on this page, then your browser supports the SVG favicon, otherwise you will see an X with a red background.

![supported](/favicon-svg.svg){: width="40"} supported

![unsupported](/favicon-no-svg.png){: width="40"} unsupported

## Code

For root
```html
<link rel="icon" type="image/svg+xml" href="/favicon.svg" />
```

For sub-dir
```html
<link rel="icon" type="image/svg+xml" href="/subdir/favicon.svg" />
```