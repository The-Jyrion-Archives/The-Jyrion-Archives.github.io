---
layout: default
title: Religion
---

# Religion 1
## Religion 2
### Religion 3
#### Religion 4
##### Religion 5
###### Religion 6

---
***
___


* a
* b
* c

>> Blockquotson

> Block1

**bold**

*italics*

1. First
2. Second
3. Thrid

`coder`

[linkerson](guilds.md)


<img alt="alt text" height="60px" src="../img/metal.png" width="60px"/>

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

term
: definition

~~The world is flat.~~

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

I need to highlight these ==very important words==.

H~2~O

X^2^

<ul>
    {% for g in site.data.guilds.guilds %}
    <p class="notice-text" face="arial" size="1">{{ g }}</p>
    {% endfor %}
</ul>

