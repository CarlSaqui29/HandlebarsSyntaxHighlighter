# Handlebars Syntax Highlighter

Supercharge your development with Handlebars Syntax Highlighter! Enjoy syntax highlighting, enhanced code readability and Handlebars code snippets.

![preview-handlebars-syntax-highlighter](./images/preview.png)

## Key Features
- Syntax highlighting
- Code snippets
- Bracket matching
- Bracket autoclosing

## Snippets
| Trigger | Description | Code Generate |
| --- | --- | --- |
| `-template` &nbsp;&nbsp;&nbsp;&nbsp; | Generates template | `<script id="id-template" type="text/x-handlebars-template"></script>`|
| `-partial` | Generates partial template | `<script id="id-partial" type="text/x-handlebars-partial"></script>` |
| `-layout` | Layout template | `{{#> layout}}{{/layout}}` |
| `-render` | Render partial template | `{{> mypartial}}` | 
| `-list` | List helper | `{{#list option-hash}}{{/list}}` |
| `-log` | Log helper | `{{#log 'log_something'}}` |
| `-if` | If condition | `{{#if foo}}{{/if}}` |
| `-ifelse` | If-Else condition | `{{#if foo}}{{else}}{{/if}}` |
| `-unless` | Unless condition | `{{#unless foo}}{{/unless}}` |
| `-with` | With helper | `{{#with object}}{{/with}}` |
| `-each` | Each helper | `{{#each object}}{{/each}}` |
---
For feature request and bugs report, submit issue on this [repository](https://github.com/CarlSaqui29/HandlebarsSyntaxHighlighter/issues). Si Vis Pacem, Para Bellum.
