# Markdown syntax
=================

## Block elements

###### Headings 1-6 and alternate heading
------ Heading / horizontal line
====== Heading line
+ Unordered List
- Unordered List
1. Ordered List
> Block quote
```
pre-formatted
code
```

## Inline elements

- *italic* / **bold** / ***bold+italic***
- [Link text](http://domain.com) or <http://domain.com> or http://domain.com
- ![Alt text](/path/to/img.jpg)
- `code`
- *italic with spaces* / **bold with spaces** / ***bold and italic with spaces***

## Bugs

- _italic_ **Issue:** The style only applies to the first word, there is no difference between bold/italic style
- __bold__ **Issue:** The style only applies to the first word, there is no difference between bold/italic style
- * Unordered List * **Issue:** Asterisk styles line as italic and have to add the extra `*` to close it
- (http://link.com "with Title optional title") **Issue:** The styling should apply to the title too
- <html> **Issue:** HTML is coloured the same as a link
