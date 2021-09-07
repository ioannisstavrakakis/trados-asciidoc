# trados-asciidoc
Trados Regular Expression File Type Setting for AsciiDoc

# Explanation of Rules
## Document structure

Specify opening and closing regular expression patterns to define the start and end points of translatable text. Text between the matched for the opening and closing patterns will be extracted for translation. An opening and closing pair must occur on the same line unless the rule is designated as multiline.

| Element | Opening Pattern | Closing Pattern | Multiline | Explanation |
| ----------- | ----------- | ----------- | ----------- | ----------- |
|             |             |             |             |             |

## Inline tags
Inline patterns define text which should be converted to inline tags. These are treated as tag pairs or recognized tokens during the translation step.

| Element | Opening Pattern | Closing Pattern | Tag type | Translatable |
| ----------- | ----------- | ----------- | ----------- | ----------- |
|             |             |             |             |             |

