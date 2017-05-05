# section1

##Images
Here's our logo (hover to see the title text):
Inline-style:
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")
Reference-style:
![alt text][logo]
[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"

##Codes and Highlighting

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
```python
s = "Python syntax highlighting"
print s
```
```
No language indicated, so no syntax highlighting.
But let's throw in a <b>tag</b>.
```

##Tables

Colons can be used to align columns.

| Tables 		| Are 			| Cool 	|
| ------------- |:-------------:| -----:|
| col 3 is 		| right-aligned | $1600 |
| col 2 is 		| centered 		| $12 	|
| zebra stripes | are neat 		| $1  	|

The outer pipes (|) are optional, and you don't need to make the raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

##Blockquotes

> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.
Quote break.
> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure th

##Inline Html

<dl>
<dt>Definition list</dt>
<dd>Is something people use sometimes.</dd>
<dt>Markdown in HTML</dt>
<dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

#Horizontal Rule

Three or more...
---
Hyphens
***
Asterisks
____
Underscores


##Line Breaks

Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a *separate paragraph*.

This line is also a separate paragraph, but...
This line is only separated by a single newline, so it's a separate line in the *same paragraph*.

##Youtube videos

<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg"
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

or

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE)

##Exercises

---

Define a variable `x` equal to 10.
```js
var x =
```
```js
var x = 10;
```
```js
assert(x == 10);
```
```js
// This is context code available everywhere
// The user will be able to call magicFunc in his code
function magicFunc() {
return 3;
} 
```

---


##Quizzes

---

Here is the introduction for the quiz
This is Question 1:
- [x] This is the proposition 1 (the correct one)
[ ] This is the proposition 2
> This is a help message when the answer to question 1 is wrong

This is Question 2:
- [ ] This is the proposition 1
- [x] This is the proposition 2 (correct)
- [x] This is the proposition 3 (correct)
> This is a help message when the answer to question 2 is wrong

---

##Import variables

### This is a test: {{ myVariable }}
>The variable is defined in book.js

###引入文件
