---
title: How to be Okay
linktitle: How to be Okay
toc: true
type: docs
date: "2019-05-05T00:00:00Z"
draft: false
menu:
  epa1316-2020:
    name: How to be Okay
    parent:
    weight: 19

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
# weight: 1
---


{{% alert thanks %}}
**We're full steam ahead on improving Academic, and we need your help!**

- :heart:
- ⭐️ [**Star** Academic on **GitHub**](https://github.com/gcushen/hugo-academic)
- :woman_technologist: [**Contribute** code, PR reviews, documentation, color themes, tutorials, etc.](https://github.com/gcushen/hugo-academic/blob/master/.github/contributing.md)
{{% /alert %}}

Rich content can be written in Academic using **Markdown**, [**LaTeX math**](https://en.wikibooks.org/wiki/LaTeX/Mathematics), and **Shortcodes**. This article gives an overview of the most common formatting options, including features that are exclusive to Academic.<!--more-->

{{% alert note %}}
*Shortcodes* are plugins which are bundled with Academic or inherited from [Hugo](http://gohugo.io/extras/shortcodes/). Additionally, **HTML** may be written in Markdown documents for advanced formatting.
{{% /alert %}}

## Sub-headings

```markdown
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

## Emphasis

```markdown
Italics with _underscores_.

Bold with **asterisks**.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough with ~~two tildes~~.
```

## Lists
### Ordered

    1. First item
    2. Another item

1. First item
2. Another item

### Unordered

    * First item
    * Another item

* First item
* Another item

### Todo

Todo lists can be written in Academic by using the standard Markdown syntax:

```markdown
- [x] Write math example
- [x] Write diagram example
- [ ] Do something else
```

renders as

- [x] Write math example
- [x] Write diagram example
- [ ] Do something else
