# hugo-simpledoc-theme

Hugo Simpledoc Theme is a simple and clean documentation theme for Hugo. Also you may use it for building a FAQ-page or generating an online book (why not?). This theme is a very-slightly-modified Hugo port of great [WPThemeDoc](https://github.com/richtabor/WPThemeDoc). 

## Screenshot

![hugo-simpledoc-theme screenshot](https://github.com/aerohub/hugo-simpledoc-theme/blob/master/images/screenshot.png)

## Features

### Original

- Clean design
- One page
- Responsive
- Easely customizable

### Added

- Hugo!

## Installation

- [Install Hugo](//gohugo.io/overview/installing/) and create a new site.
- Install hugo simpledoc theme. Inside your new Hugo project run:

```
$ cd themes
$ git clone https://github.com/aerohub/hugo-simpledoc-theme
```

# Writing documentations

Then take a look inside the [`exampleSite`](//github.com/aerohub/hugo-simpledoc-theme/tree/master/exampleSite) folder of this theme. You'll find a file called `config.toml` and a folder `archetypes`. Copy them into the root folder of your Hugo site.

## Configuration

Open just-copied `config.toml` and fill it with your data. Pay attention for top menu items.

Now you are ready to create your documentation

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

Write your doc chapter and give it a weight. You may organize your content as you like (even with folders) but **All the docs are ranged by weight here!** Well, the structure of your docs may look like this:

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

# Serving and building

## Test your site

In order to see your site in action, run Hugo's built-in local server. 

    $ hugo server -w

Now enter `localhost:1313` in the address bar of your browser.

## Build your site

Just run

	$ hugo

You'll find your documentation files in `public` folder in the root of Hugo project.

# Credits and Thanks

Many thanks go to:

- [spf13](https://github.com/) & [Hugo](https://github.com/gohugoio/hugo)
- [Rich Tabor](https://github.com/richtabor) & original [WPThemeDoc](https://github.com/richtabor/WPThemeDoc)

# License

The MIT License (MIT)

Copyright (c) 2017 Pavel Kanyshev

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
