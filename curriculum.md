# David Teaches Coding
This is a _very_ quick crash course in some of the things I have learned from [__DevMountain__](www.devmountain.com "DevMountain's Homepage").

---
### 01. Intro to Terminal and HTML
In this lesson, we will organize our dock, learn some basic Terminal commands, and make our very first website using simple HTML.
###### 01.01 - Organizing the Dock

Clean up your dock! Remove all items that you don't use regularly, and add Terminal and Chrome to the Dock so that you can easily access them. They will soon be two of your best friends.

###### 01.02 - Terminal Navigation

We are going to use the following commands to make a directory (aka folder) named helloWorld. Inside of that folder, we are going to create a file called index.html.

`pwd` print working directory.

`ls` list sorted. `l` list unsorted.

`cd dir_name` change directory. `cd` go up one directory.

`mkdir dir_name` make directory.

`touch file_name` create file.

`nano file_name` edit file in nano.

`open file_name` open file using default program.

###### 01.03 - HTML Intro

HTML is a language used by browsers to display content on your screen. With very few exceptions, HTML content is separated using opening and closing tags that look like this `<html>` and this `</html>` respectively. We are going to make a very simple website using nano.

__01.03.01 - HTML Basic Document Setup__

Type `nano index.html` to open nano inside of terminal. We can use this simple text editor to write the code for our first website.

Add `<html></html>` tags that will enclose your entire document. Within those tags add `<head>` and `<body>` opening and closing tags. Inside of your head, add `<title>My First Website</title>` which will display a title in your website's tab. Add the text `Hi, Universe` wrapped inside of an `<h1>` tag inside of your body tags.

At this point, your index.html file should look like this:

```
<html>
<head>
<title>My First Website</title>
</head>
<body>
<h1>Hi, Universe</h1>
</body>
</html>
```
`<-- this is a bug
Remember, HTML is very forgiving. Multiple spaces, including line breaks, are treated as a single space.

If your index.html file looks correct, hit `ctrl` + `o` to save your file. Hit enter if the name is "index.html". Hit `ctrl` + `x` to exit nano.

You should still be in your project folder. Enter `open index.html` to open your website in your default browser.

Congratulations! You have just made your first website.

__Extra Credit:__ Add `style="background-color: red"` to your body tag. Use `alt` + `tab` to navigate to your browser, and `alt` + `r` to refresh the page. Add `style="font-family: helvetica"` to your h1 tag. Refresh your browser again. Congratulations! You just did some CSS, and you should now have a red background and some helvetica text on your page.

### 02. Intro to GitHub
create a github account
create a repo
git clone
git add
git commit
git push
git status

### 03. Intro to CSS
In this lesson, we will cover more Terminal commands, more HTML tags, and create a CSS file to handle our styles.

__Terminal commands:__

mv
cp
rm -rf
using .
using asterisk
using /

__HTML:__

header
footer
div
span
p
a
img
background
background-image
link
class
id

__CSS:__

height
width
strong
font-weight
font-family
font-size
color
.
#


### 04. CSS Position and Box-Model
box-model
margin
	trbl
	auto
padding
border
box-sizing border-box
position
	static
	absolute
    relative
    fixed
top, right, bottom, left
display
	none

Selectors
multiples
children

Terminal
Using &&

Github
Detaching HEAD
git branch


------------------------------------
---
---




# My Markdown Reference
##### Ignore the following content.
When you see `this` You'll know I am writing code.

```javascript
This is also code!
```

This is a table:

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

Here is a quotation:
> I am a quotation.
> You know you like quotations.

---

Markvi usage bugs:
***
1. First ordered list item
⋅⋅* Should this be an asterisk or just an indent?
1. Actual numbers don't matter, just that it's a number
⋅⋅1. Should this show the dots?
* Unordered list can use asterisks. (this is numbered)
- Or minuses (so is this)
+ Or pluses (so is this. why come?)

Can we make it so when I change documents it goes to where I was last reading?

[arbitrary case-insensitive reference text]: https://www.mozilla.org

The above link doesn't show up for some reason.

Javascript/python syntax highlighting isn't happening:
```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```

Are hrs supposed to be asterisks, dashes, or underscores, or do they all display the same?
***
---
___
***
That's doing some weird stuff.

---
---
---
---
---

This is also kind of odd:
Traditional markdown needs two spaces at the end of a line to start a newline (like so: `  `).
To switch back to that method, simply set `breaks` to `false` in the options near the bottom of `scripts/markdown.js`

Maybe because it is not set in options? Needs a fix maybe?

Should md text in editor become italic? I think not.

Had a problem with text being incorrectly white/gray after a block of code.

When copying all and pasting, first 4 characters were omitted. Why come?
