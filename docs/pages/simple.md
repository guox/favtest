---
title: Simple Mode
description: The simple mode will only use large sized icons as favicons, making them easier to maintain and design.
lang-ref: simple
permalink: /simple/
---

If there is no special requirement for favicons to be displayed on different browsers and devices, simple mode is simpler, meaning that we will only use the largest size icons as favicons, easier to maintain and design.

With simple mode please note:

- Chrome will ues apple-touch-icon on mobile devices
- Windows will use mstile-150x150 for 

## Code

For root dir
```html
<link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png?v={{ site.time | date: "%s" }}">
<link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png?v={{ site.time | date: "%s" }}">
<link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png?v={{ site.time | date: "%s" }}">
<link rel="manifest" href="/site.webmanifest">
<meta name="msapplication-TileColor" content="#da532c">
<meta name="theme-color" content="#ffffff">
```
