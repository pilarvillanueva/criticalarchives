---
layout: post
title: "Writing in Markdown"
modified:
categories: blog
excerpt:
tags: []
author: halperta
image:
  feature:
---

# Writing an article in markdown

[Markdown](https://en.wikipedia.org/wiki/Markdown) is a simple formatting language for writing text. It works a lot like HTML, only it's a lot easier to use.

You'll be writing your blog post in Markdown. That means that you should compose the text (or copy the text) into a *plain text editor*. Notebook is one popular program. I like to use [Sublime](https://www.sublimetext.com/). Follow these instructions to get started:

## YAML header
Your file should begin with a header that looks exactly like this (including the dashes):

```
---
layout: post
title: "ENTER YOUR TITLE HERE"
modified:
categories: blog
excerpt: YOU CAN INCLUDE A SENTENCE FROM THE BLOG HERE IF YOU WANT.
tags: []
author: "ENTER YOUR AUTHOR ID HERE"
image:
  feature:
---
```

## Content
Below the YAML header, you should write the post just as you ordinarily would do. You can find detailed instructions on how to write in Markdown [here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet), or use the following tips:
```
Headers:  
    # Heading One  
    ## Heading Two  
    ### Heading Three (etc)  

Formatting:  
	*italics*  
	**bold**  

Links:  
	[link text in brackets](url-in-parentheses)

Line Breaks:  
	End the previous line with two spaces,  
	then begin writing on the following line to create a line break.  

Accents:  
	Accents and other diacritics (á, ñ, ü)  
	can be typed into the text as normal.

Lists:
	Use 
		* text
	to create a disordered list.
	Use 
		1. text
		2. text 
		3. text 
	to create an ordered list.

```
