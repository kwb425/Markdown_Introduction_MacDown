[![tag][a]][1]
[![release][b]][2]
[![download][c]][3]
# Markdown Intro
Recommend you to use editors like [Atom][4] (github), [MacDown][5] (MIT), etc. 

To see source code, please download README.md and call it from any editor.

---

## Table of Contents (click for fast navigation.) <a name="anchor_1"></a>
1. [Text Control](#anchor_2) <br></br>
2. [Links Control](#anchor_3) <br></br>
3. [Table Control](#anchor_4) <br></br>
4. [References](#anchor_5) <br></br>

## Text Control <a name="anchor_2"></a> [up](#anchor_1)
<!-- As you can see below, numbering of lists is not important.-->
1. A horizontal line (bold line above):  
	
	```
	Syntax: --- (or more, like ----, ------, ...)
	```
2. Comments:
	
	```
	Syntax (HTML): <!--anything between these signs will be ignored.-->
	```
3. Titles:  
	
	```
	Syntax: # biggest title, ## smaller, ### smaller, ...
	```
4. Emphasizing:  
	* **bold**, __bold__, *italic*, _italic_

		```
		Syntax   : **bold**, __bold__, *italic*, _ italic_  
		Shortcuts:    command + b    ,    command + i      
		Tips     : bullets can be created by either -, +, or *.  
		```
5. Quotation:
	> This line is quoted.

	`Syntax: > quotation, >> double embedded, >>> triple embedded, ...`		
6. Raw printing:  
	
	```
	Syntax: \ (e.g., \#, \*, \>, \_, \\, etc)
	```
7. Line feed (next line):
	
	```
	Syntax (HTML)    : <br>texts<\br>
	Syntax (Markdown): press space bar twice.
	```
8. Line cancelation: ~~strikethrough~~
	
	```
	Syntax (HTML)    : <del>text</del>
	Syntax (Markdown): ~~strikethrough~~
	```
9. Abbreviation (not compatible with github flavored markdown): <abbr title="National Aeronautics and Space Administration">NASA</abbr>
	
	```
	Syntax (HTML): <abbr title="full name">abbreviation</abbr>
	```

## Links Control <a name="anchor_3"></a> [up](#anchor_1)
1. Annotation (not compatible with github flavored markdown): footnote[^1] 
	
	```
	Syntax: text[^n]                 # Inline Markdown
	Syntax: [^n]: annotation         # Reference Markdown
	Syntax: 'n' is positive integer.
	```
2. Links in page:
	
	```
	Syntax (making destination)        : <a name="anchor_name"></a>
	Syntax (heading to the destination): [click_tag](#anchor_name)
	```
3. Links to internet address (or maybe an email):
	
	```
	Syntax (direct)         : <address>, <email>, ...
	Syntax (semi-direct)    : [tag]                   # Inline Markdown
	Syntax (semi-direct)    : [tag]: address          # Reference Markdown
	Syntax (indirect)       : [tag](address)
	Syntax (double indirect): [tag][another_tag]      # Inline Markdown
	Syntax (double indirect): [another_tag]: address  # Reference Markdown
	```
4. Uploading an image:
![Markdown_logo][d]
	
	```
	Syntax (semi-direct)    : ![tag]                     # Inline Markdown
	Syntax (semi-direct)    : ![tag]: address            # Reference Markdown
	Syntax (indirect)       : ![tag](address)
	Syntax (double indirect): ![tag][another_tag]        # Inline Markdown
	Syntax (double indirect): [another_tag]: address     # Reference Markdown
	Tips (Linked image)     : [![tag](address)](address)
	```

## Table Control <a name="anchor_4"></a> [up](#anchor_1)
1. Sample table: 

| Item     | Value | Qty   |
| :------- | :---: | ----: |  
| Computer | 23134 |  51   |  
| Phone    | 12345 |  123  |  
| Apple    |  11   |  4341 |  
```	
Syntax: draw a table-like structure.
| Item     | Value | Qty   |
| :------- | :---: | ----: |         # Alignment (left, center, right)
| Computer | 23134 |  51   |
| Phone    | 12345 |  123  |
| Apple    |  11   |  4341 |
```
	
## References <a name="anchor_5"></a>  [up](#anchor_1)
Please check Git repository for [latest update][6]

Please send any question to: <kwb425@icloud.com>

[^1]: Link between the footnote and it's reference
<!--Links to addresses, reference Markdowns-->
[1]: https://github.com/kwb425/Markdown_Introduction_MacDown/tags
[2]: https://github.com/kwb425/Markdown_Introduction_MacDown/releases
[3]: https://github.com/kwb425/Markdown_Introduction_MacDown/releases
[4]: https://atom.io                       
[5]: http://macdown.uranusjr.com
[6]: https://github.com/kwb425/Markdown_Introduction_MacDown
<!--Links to image, reference Markdown-->
[a]: https://img.shields.io/badge/Tag-v1.1-red.svg?style=plastic
[b]: https://img.shields.io/badge/Release-v1.1-green.svg?style=plastic
[c]: https://img.shields.io/badge/Download-Click-blue.svg?style=plastic
[d]: https://github.com/kwb425/Git_Markdown_Introduction/blob/master/Markdown_Introduction/Markdown_logo.png?raw=true
#### Final Tip
Do NOT NOT NOT NOT NOT feed line (new line) unless you are forced to do so.

This system is extreamly sensitive to spaces, and I want you to stay sane.