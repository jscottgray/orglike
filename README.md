# OrgLike - Hugo theme

Archie is a minimal and clean theme for hugo with a markdown-ish UI.

Forked from [Archie Theme](https://github.com/athul/archie.git) which was forked from [Ezhil Theme](https://github.com/vividvilla/ezhil)

## Feature

- Google Analytics Script
- Callouts
- Tags
- Auto Dark Mode(based on system theme)
- tl:dr; frontamatter

## Installation

In your Hugo website directory, create a new folder named theme and clone the repo

```bash
$ mkdir themes
$ cd themes
$ git clone https://github.com/jscottgray/orglike.git
```

Edit the `config.toml` file with `theme="orglike"`
For more information read the official [setup guide](https://gohugo.io/overview/installing/) of Hugo.

## Writing Posts

Create a new `.md` file in the _content/posts_ folder

```yml
---
title: Title of the post
description:
date:
tldr: (optional)
draft: true/false (optional)
tags: [tag names] (optional)
---
```

## Credits

Forked from [Archie Theme](https://github.com/athul/archie.git) which was forked from [Ezhil Theme](https://github.com/vividvilla/ezhil) and Licensed under MIT License
Inspired by design of blog.jse.li

---

## Config of the Demo Site

```toml
baseURL = "/"
languageCode = "en-us"
title = "Orglike"
theme="orglike"
copyright = "© jscottgray"
# Code Highlight
pygmentsstyle = "monokai"
pygmentscodefences = true
pygmentscodefencesguesssyntax = true

paginate=5 # articles per page

[params]
	mode="auto" # color-mode → light,dark or auto
	featherIconsCDN=true
	subtitle = "Minimal and Clean [blog theme for Hugo](https://github.com/jscottgray/orglike)"

# Main menu Items

[[menu.main]]
name = "About"
url = "/about"
weight = 1

[[menu.main]]
name = "Tags"
url = "/tags"
weight = 2
```
