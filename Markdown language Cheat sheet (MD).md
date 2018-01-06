#Markdown Cheat Sheet

_Many thanks to [markdowntutorial.com](www.markdowntutorial.com) and [daringfireball.net](daringfireball.net/projects/markdown/)_

###Bold
surround with \*\* \(two asterisks)
_Example:_ `this is **bold** text`

###Italics
surround text with \* \(single underscore)
_Example:_ `this is _really_ interesting`

###Headers
There are 6 \(like `<h1>` to `<h6>`)
- For Header1 you prefix it with one \#.
- For Header2, you prefix it with two \#\#s.

###Hyperlinks

There are two types:

* **Inline Links**
 * Surround the **text** in `[]`
 * Surround the **link** in `()`
   _Example:_  'Go to [my home page](dickdonohue.com) for more info.`

* **Reference links**
You put the actual link at the bottom of the document.
 * Surround the **text** in `[]` \(square brackets)
 * followed immediately by the reference \(like a tag\) also surrounded in brackets
  * The reference link listed elsewhere is `[]` followed by a colon
 _Example:_

`  Do you want to [see something fun][a fun place]?`

`  `

`[a fun place]: www.github.com`


###Images
Same as a hyperlink, except that it is prefixed with a \! \(exclamation point)
The text becomes the alt-text for the image.

###Block quote
Prefix with a \> \(greater than).

* Can be a sentence or a paragraph
* If you have multiple paragraphs (line feeds) just prefix all with >
* _Example_    `>”The Lord is my sheperd”`

###Lists
* **Unordered** - prefix list items with a single \* \(asterisk with a space after it)
* **Ordered list** - prefix list item with number followed by a period
To create multiple levels, just prefix with an additional space \(to indent)

###Paragraphs
* To simulate a `<p>` insert a blank line after the text
* To simulate a `<br>` suffix the line with two trailing spaces

###Code
* To show code inline surround it with a \` \(back tick)
* To show a block of code surround it with \`\`\` \(three backpacks)