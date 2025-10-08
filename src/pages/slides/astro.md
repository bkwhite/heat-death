---
layout: '@layouts/slides/Basic.astro'
title: 'What is astro'
image: '/astro.png'
imageAlt: 'astro logo'
---
- [astro](https://astro.build/) is a barebones JavaScript framework designed for building content driven websites
- components are built using `.astro` files
- framework agnostic components (components from other frameworks can be used via `Islands🏝️`)

```js
___
// server side JS goes here
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
  document.querySelector('div');
</script>
```
