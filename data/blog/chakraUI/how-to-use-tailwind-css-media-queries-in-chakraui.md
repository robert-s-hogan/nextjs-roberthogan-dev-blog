---
title: How does chakra ui handle tailwind media queries (React)
date: '2022-06-24'
summary: 'Here is how I handled ChakraUI to create responsive sizes on ChakraUI components'
tags: ['react', 'chakraUI', 'TailwindCSS', 'guide']
draft: false
---

Here is the official ChakraUI link detailing what I am going to go over: (link)[https://chakra-ui.com/getting-started/comparison#responsive-styles-]

There are two ways to create call the ChakraUI API:

```js
Array syntax: <Img w={[16, 32, 48]} src="...">
```

```js
Object syntax: <Img w={{ base: 16, md: 32, lg: 48 }} src="..." />
```
