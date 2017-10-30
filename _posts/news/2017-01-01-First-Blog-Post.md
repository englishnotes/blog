---
layout: default
title: My first blog Posts
meta: first Posts
category: news
description: A short description of your site's purpose

---

# Baslik

sadf
sdf
af
asd
sdfsd

f
## alt baslik


First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column


# Learn Jekyll in 12 Steps




## 1. Installation

```bash
# update gem
$ sudo gem update --system
# install jekyll
$ sudo gem install jekyll
```

## 2. Create simple jekyll website and run

```bash
$ touch index.html
$ nano index.html
```
paste into some html.
```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>my title</title>
  </head>
  <body>
    <h1>Test</h1>
  </body>
</html>
```
```bash
# create jekyll configuration file.
$ touch _config.yml

```
content of \_config.yml
```xml
markdown: redcarpet
baseurl: /blog
expect: ['readme.md']
```
run jekyll
```bash
$ jekyll serve
## further example
## jekyll serve --watch --baseurl ""
# navigate http://127.0.0.1:4000

```
