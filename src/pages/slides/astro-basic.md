---
layout: '@layouts/slides/Basic.astro'
title: 'Basic astro component'
---

```html
___
// server side JS goes here
// things like API calls & data formatting
const { prop } = Astro.params;
___

<div>
  content {prop}
</div>

<style>
  div {
    padding: 16px;
  }
</style>

<script>
  // client side JS goes here
  // things like event listeners, DOM manipulation
  document.querySelector('div');
</script>
```
