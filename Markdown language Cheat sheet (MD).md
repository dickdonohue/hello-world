# Markdown Cheat Sheet

_Many thanks to [markdowntutorial.com](http://www.markdowntutorial.com) and [daringfireball.net](http://daringfireball.net/projects/markdown/)_

###### Last updated: Jan 24, 2017

### Bold
Surround text with `**` \(two asterisks)
_Example:_ `this is **bold** text`

### Italics
Surround text with `*` \(single underscore)
_Example:_ `this is _really_ interesting`

### Headers 
There are 6 \(similar to `<h1>` to `<h6>`)
- For Header1 you prefix it with one `#`.
- For Header2, you prefix it with two `##`s.
- _be sure to leave a space after the last \#!_
_Example:_
```
# Heading 1
#### Heading 4
```

### Hyperlinks  
There are two types:  

1. **Inline Links**  
   - Surround the **text** in `[ ]`
   - Surround the **link** in `( )`  
   _Example:_  'Go to [my home page](http://dickdonohue.com) for more info.`

2. **Reference links**    
You put the actual link somewhere else \(like the bottom of the document.)
   * Surround the **text** in `[ ]` \(square brackets)
   * followed immediately by the reference \(like a tag\) also surrounded in brackets
   * The reference link \(listed elsewhere) is `[ ]` followed by a colon  
 _Example:_  
```
Do you want to [see something fun][a fun place]?  
  :
  :
[a fun place]: www.github.com
```

### Images  
Same as a hyperlink, except that it is prefixed with a `!` \(exclamation point)
The text becomes the alt-text for the image.  
_Example:_ `![my profile pic](https://avatars1.githubusercontent.com/u/15901042?s=400&v=4)`  

Which renders to this: 
![my profile pic](https://avatars1.githubusercontent.com/u/15901042?s=400&v=4)

### Block quote  
Prefix with a `>` \(greater than).  
* Can be a sentence or a paragraph
* If you have multiple paragraphs (line feeds) just prefix all with `>`
_Example_    
`>"The Lord is my shepard"`

### Lists  
* **Unordered** - prefix list items with a single `*`  or `-` \(asterisk or minus)  
  * _must be followed by a space_
* **Ordered list** - prefix list item with number followed by a period
To create multiple levels, just prefix with an additional space \(to indent)  
_Example:_ 
```
1. Item 1
   * Item 1.1
2. Item 2 
```
Which renders as:  
1. Item 1
   * Item 1.1
     * Item 1.1.1
2. Item 2  

### Paragraphs  
* To simulate a `<p>` \(a soft break), insert a blank line after the text
* To simulate a `<br>`\(a hard break), suffix the line with two trailing spaces

### Code  
* To show code inline surround it with a  ```  `  ``` (back tick)
* To show a block of code surround it with `  ```  ` (three backpacks)

### Escaping 
There are times when you don't want the Markdown effect.  For example, if you want to show text
that is actually in  parenthesis, \(like this), you need to prefix it with a `\` \(a backslash).
_Example:_  `I never forget a face \(but in your case, I'll make an exception`

### Lessons I learned:
1. Be sure your editor does not trim trailing spaces when you save your files.  Otherwise, you lose 
all your soft breaks. 
2. For lists, the bullet character \(either `*` or `-`) needs to have a space after it!
   - also, when indenting lists, put the bullet in the same column as the first character of text 
 level above it.  
3. There are folks (Github and Others) that have created extensions to the original Markdown 
 language.  For example, the Code mark-up is not part of the original definition. Other formatting 
 that is not part of the original design includes 
 [codes for making tables](https://help.github.com/articles/organizing-information-with-tables/).
4. Escaping challenges
   - To show a _single_ backtick \(``` ` ```) as code in a Markdown document, you need to surround 
   it with _triple_ backticks \(` ``` `)
   - To show _triple_ backticks \(` ``` `) as code in a Markdown document, you will need to 
   surround it with a _single_ backtick \(``` ` ```)
   - or if you don't need to show it as "code", you can just prefix it with a backslash  \(`\`)
