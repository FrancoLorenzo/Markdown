[//]: <> (This is a comment. Look for more information here: https://www.markdownguide.org/basic-syntax/)

> **Note on how to use this tutorial file:** Edit this document to learn more about the different Markdown syntaxis in the comments.

# Markdown markup language tutorial. 
## What is Markdown?

Markdown is a lightweight markup language that you can use to add formatting elements to plaintext text documents. Created by [John Gruber](https://daringfireball.net/projects/markdown/) in 2004, Markdown is now one of the world’s most popular markup languages.

## What’s Markdown Good For?
Markdown is a fast and easy way to take notes, create content for a website, and produce print-ready documents.

For more information check this [link](https://www.markdownguide.org/getting-started/).


[//]: <> (The following dashes render a horizontal rule tp separate the content.)
----------------------------------------

# Markdown basic syntax
# This is heading level 1
## This is heading level 2
### This is heading level 3
#### This is heading level 4
##### This is heading level 5

Alternative for heading level 1
================================

Alternative for heading level 2
--------------------------------

This is an example of a parragraph, as a best practice don't use tabs or spaces in front of your parragraphs.
Line breaks are represented with a single enter key.

Here is our second parragraph, use trailing white space or the < br > HTML tag at the end of the line.

----------------------------------------

## Bold text
This is a **bold text**.
This is a second __bold text__. Not recommended as a best practice.

----------------------------------------

## Italic text
This is an *italic text*.

This is an _italic text_.

----------------------------------------

## Bold and italic text
This is a ***bold and italic text***.

This is a second ___bold and italic text___. Not recommended as best practice.

This is a third __*bold and italic text*__.

This is a fourth **_bold and italic text_**.

----------------------------------------

## Strikethrough
This is an example of ~~strikethrough text~~.

----------------------------------------

## Blockquotes
>To create a blockquote, add a > in front of a paragraph.

>Blockquotes can contain multiple paragraphs. You just need to add a > in front of a parragraph and on the blank lines between the paragraphs.
>
>Here is the second parragraph.

----------------------------------------

## Nestes blockquotes
>To create a blockquote, add a > in front of a paragraph.
>
>>Blockquotes can be nested. Add a >> in front of the paragraph you want to nest.

----------------------------------------

## Blockquotes with Other Elements
> #### This is a heading level 3
>
> - Unordered list item 1.
> - Unordered list item 2.
>
>  *Italic text* can also be contained **here**.

----------------------------------------

## Lists
### Ordered lists
1. First item
2. Second item
3. Third item
4. Fourth item

### Unordered lists
- First item
- Second item
- Third item
- Fourth item

----------------------------------------

## Code blocks
`<html>This is a code example</html>`

``To escape Backticks a word or phrase as code, enclose it in double backticks (`).``

----------------------------------------

## Images
![Markdown icon](https://github.com/FrancoLorenzo/Markdown_tutorial/blob/main/Images/markdown-icon.png)

----------------------------------------

## Email addresses
This is an example of email address: <fake.email@example.com>.

----------------------------------------

## Tables
To add a table, use three or more hyphens (---) to create each column’s header, and use pipes (|) to separate each column. You can optionally add pipes on either end of the table.

| Column 1    | Column 2    |
| ----------- | ----------- |
| Item 1      | Item 3      |
| Item 2      | Item 4      |


### Table text alignment
| Column 1    | Column 2    | Column 3    |
| :---        |    :----:   |        ---: |
| Item 1      | Item 3      | Item 5      |
| Item 2      | Item 4      | Item 6      |

----------------------------------------

## Fenced Code Blocks
```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

## Syntax Highlighting
This is an example of a Json code block:

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```
----------------------------------------

## Heading IDs
This is an example of [heading IDs](#What-is-Markdown?).

----------------------------------------

## Task list
- [x] To do item #1.
- [ ] To do item #2.
- [ ] To do item #3.


----------------------------------------

## Emoji
There are two ways to add emoji to Markdown files: copy and paste the emoji into your Markdown-formatted text, or type emoji shortcodes.

Gone camping! :tent: Be back soon.

That is so funny! :joy:

----------------------------------------