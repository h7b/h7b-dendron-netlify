---
id: Hs0V11FbDMMurMrFArdkC
title: Note Reference
desc: ''
updated: 1646585347137
created: 1636948922923
---
# How to reference content from other notes and embed them in your current note (transclusion)

ref: [dendron wiki](https://wiki.dendron.so/notes/f1af56bb-db27-47ae-8406-61a98de6c78c/)

Currently, Dendron supports 4 types of references to help you control the amount of content that gets embedded:
- note references
    - syntax: `![[name.of.note]]`
- header references
    - syntax: `![[name.of.note#header]]`
- block references
    - syntax: `![[name.of.note#^important-paragraph]]`
- range references
    - syntax: `![[name.of.note#starting-header:#ending-header]]`

## Additional Options

### Line Offset
You can use line offsets to skip a number of lines when using a header reference. The syntax is `,{number}`. 

Example of using a note reference offset to offset an initial heading, skipping the actual header when doing the embedding.

`![[demo.embed.block#head1,1]]`

### Wildcard Headers as a Range Boundary

For example, the following would reference the content from header1 to the next header.
`![[demo.embed.block#head1:#*]]`