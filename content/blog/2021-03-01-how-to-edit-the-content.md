---
title: How to edit the content
description: And what to expect when running a repo-based CMS
---

It is easy to write **markdown**-*enabled* content like this placeholder text, with support for images and even code snippets.

If you are in local development-mode (`npm run dev`) you can double-click here to edit and save this page quickly.


```js{1,4}[posts.vue]
formatDate(dateString) {
  const date = new Date(dateString)
  return date.toLocaleDateString(process.env.lang) || ''
}
```


