---
title: "Writing Documentation"
date: 2017-12-12T00:57:40+03:00
anchor: "writing-documentation"
weight: 30
---
OK, all you need is just write!

Run in the root of your project:

```
hugo new my-first-doc-item.md
```

Then open the file with your favorite text editor and you will see something like this:

```
---
title: "My First Doc Item"
date: 2017-12-12T00:57:40+03:00
anchor: "my-first-doc-item"
weight: 
---
```

Write your doc chapter and give it a weight. You may organize your content as you like (even with folders) but **All the docs are ranged by weight here!**


Well, the structure of your docs may look like this:

```
content
├── credits-thanks-and-license.md
├── getting-started.md
├── hugo-simpledoc-theme.md
├── license.md
├── serving-and-building.md
└── writing-documentation.md
```

but they are ordered by weight you set in frontmatter.