# Markdown grammar

Our intention is to _follow the specifications_ as they are defined in the [latest version (0.22)](http://spec.commonmark.org/0.22/) of [CommonMark](http://www.commonmark.org/), and to allow the user to dynamically **add flavor(s)** of their own choosing; `Github` or `Pandoc` for example.

---

### Limitations

Unfortunately however, because of how Atom parses grammar, certain things are simply impossible or unrealistic to detect/support. If you experience any issues above a reasonable level of annoyancy, please [create an issue](issues/new/) (or contact us directly) and supply as much relevant information as possible.

The list below gives an overview of what's _not_ in this package, and where possible a summary of what lead to that decision.

- __Setext headers__ are simply impossible to detect.
- __Indented code blocks__ have been implemented but are disabled. We can't detect if indentation belongs to a code block or a list, and _fenced code blocks_ are a good alternative.

---

In the summaries below you can get an idea of the progress of our work.

## CommonMark

### Leaf blocks

Leaf blocks are blocks that can _not_ contain other blocks.

| Section | Specs | Contact |
| ------- | ----- | ------- |
| Horizontal rules | 24 of 25 | @burodepeper |
| ATX headings | 24 of 25 | @burodepeper |
| Fenced code blocks | - | @burodepeper |
| HTML blocks | _in progress_ | @burodepeper |
| Links reference definitions | - | @burodepeper |

### Container blocks

Container blocks are blocks that _can_ contain other blocks.

| Section | Specs | Contact |
| ------- | ----- | ------- |
| Block quotes | in progress | @burodepeper |
| Lists | 19 of 19 | @burodepeper |

### Inlines

| Section | Specs | Contact |
| ------- | ----- | ------- |
| Backslash escapes | 14 of 22 | @burodepeper |
| Entities | 27 of 33 | @burodepeper |
| Code spans | 6 of 15 | @burodepeper |
| Emphasis and strong emphasis | 92 of 129 | @burodepeper |
| Links | _in progress_ | @burodepeper |
| Images | - | @burodepeper |
| Autolinks | - | @burodepeper |
| Raw HTML | in progress | @burodepeper |
| Hard line breaks | - | @burodepeper |
| Soft line breaks | - | @burodepeper |

---

## Flavors

| Section | Status | Contact |
| ------- | ----- | ------- |
| Dynamic grammar selection | - | @leipert |
| Less verbose specs | _in progress_ | @leipert |
| Improved fenced code blocks | - | @leipert |

### Github flavored Markdown

See: https://help.github.com/articles/github-flavored-markdown/

| Section | Specs | Contact |
| ------- | ----- | ------- |
| Strikethrough | - | @burodepeper |
| Tables | - | @burodepeper |

### Pandoc flavored Markdown

| Section | Specs | Contact |
| ------- | ----- | ------- |
| TODO @leipert | - | - |

### CriticMarkup

See: https://github.com/CriticMarkup/CriticMarkup-toolkit/

| Section | Specs | Contact |
| ------- | ----- | ------- |
| TODO @burodepeper | - | - |
