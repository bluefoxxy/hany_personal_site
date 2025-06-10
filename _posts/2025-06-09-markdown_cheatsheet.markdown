---
layout: post
title:  "Markdown Cheat Sheet"
date:   2025-06-09 11:40:59 -0600
categories: Sean Blake
---

Jekyll-Markdown-Cheat-Sheet

This cheat sheet provides a quick overview of all the Markdown syntax elements.
Table of contents

    What is Markdown?
    Basic syntax
    Extended syntax
    Further reading

What is Markdown?

Markdown is a lightweight and easy-to-use markup language for web writers. Markdown allows you to add formatting elements to plaintext documents and then convert them to structurally valid HTML.

Markdown syntax can be divided into two broad categories. These categories are (1) basic syntax outlined in the original design document and (2) extension of basic syntax for added capability and features.

Refer to Markdown cheat sheet for more examples.
Basic syntax

These elements are defined in the original Markdown design document and can be used in all Markdown applications.

Detailed information and examples can be fount at basic syntax guide.
Headings
H1
H2
H3
H4
H5
H6

# H1
## H2
### H3
#### H4
##### H5
###### H6

Blockquote

    # H1
    ## H2
    ### H3
    #### H4
    ##### H5
    ###### H6


Paragraph

Here’s a paragraph.

Here's a paragraph.

Line break

Here’s another one
with a line break.

Here's another one  
with a line break.

Bold

bold text
bold also

**bold text**  
__bold also__

Italic

italic text
italic also

*italic text*  
_italic also_

Blockquote

    blockquote text

> blockquote text

Ordered list

    Item 1
    Item 2
        Item 2a
        Item 2b
    Item 3

1. Item 1
1. Item 2
    1. Item 2a
    1. Item 2b
1. Item 3

Unordered list

    Item
    Item
        Indented item
        Indented item
    Item

- Item
- Item
    - Indented item
    - Indented item
- Item

Inline code

This is an inline code.

This is an inline `code`.

Horizontal rule

Here’s some text.

Here’s more text.

Here's some text.

---

Here's more text.

Link

title

[title](https://www.example.com)

Image

Git Branching

![alt text](image.jpg)

Extended syntax

These elements provide additional features by extending the basic syntax. Not all Markdown applications support these elements and each Markdown Flavor differs slightly.

Note that GitHub.com uses its own version of the Markdown syntax called GitHub Flavored Markdown and some features are only available in the issues and pull requests.

Refer to Jekyll Markdown coverage for a list of supported elements.

Detailed information and examples can be fount at extended syntax guide.
Table
Syntax 	Description
Header 	Title
Paragraph 	Text

| Syntax    | Description |
| --------- | ----------- |
| Header    | Title       |
| Paragraph | Text        |

Fenced code block

{
    "firstName": "John",
    "lastName": "Doe",
    "age": 25
}

```
{
    "firstName": "John",
    "lastName": "Doe",
    "age": 25
}
```

Syntax highlighting

{
    "firstName": "John",
    "lastName": "Doe",
    "age": 25
}

```json
{
    "firstName": "John",
    "lastName": "Doe",
    "age": 25
}
```

Footnote

Here’s a sentence with a footnote reference. 1

Here's a sentence with a footnote reference. [^1]

[^1]: This is the footnote.

Abbreviation

The SMTP is a communication protocol for email transmission.

*[SMTP]: Simple Mail Transfer Protocol
The SMTP is a communication protocol for email transmission.

Heading ID
Awesome Heading

### Awesome Heading {#custom-id}

Definition list

Caution

Not supported by Jekyll.

term
: definition

Strikethrough

~text~

~~~text~~~

Task list

    Read the Markdown guide
    Review the style guide
    Stay awesome!

- [x] Read the Markdown guide
- [ ] Review the style guide
- [ ] Stay awesome!

Emoji characters

👍🤓

👍🤓

Emoji shortcodes

Caution

Not supported by Jekyll.

:rocket:

Automatic URL linking

Caution

Not supported by Jekyll.

https://www.example.com

Disabling automatic URL linking

Caution

Not supported by Jekyll.

`https://www.example.com`

HTML

HTML test paragraph.

<div>
    <p>HTML test paragraph.</p>
</div>

Further reading

The Markdown Guide provides a detailed overview of Markdown, how it works, and what can be done with it.

Hands on Markdown experience can be achieved by completing The Markdown Tutorial or simply experimenting with online editors such as StackEdit.

A collection of awesome markdown goodies (libraries, services, editors, tools, cheatsheets, etc.) can be found at Awesome Markdown Repo on GitHub.

    This is the footnote. ↩

This site is open source. Improve this page.
