![brackets.jpg](http://plinth.org/techtalk/wp-content/uploads/2017/02/sqbrackets.jpg)

# VIM-SURROUND PLUGIN CHEAT SHEET

* This markdown file was entirely done with the **VIM EDITOR** & the commands below.
* All of images used was resize with [Resizeimage.net](http://resizeimage.net/ "website for resizing image") & upload to [Imgur.com](http://imgur.com "website for uploading image")
* Gif was take with [Peek](https://github.com/phw/peek) PPA

---

## EXAMPLE

![surroundgif](https://i.imgur.com/e7r4JvN.gif)

Command: `ysw@`

---

## SOME COMMANDS

In this exemple im using the sentence : **Welcome to CS** 

### ***Non-exhaustive list of surrounding characters***

```
* (parenthesis)  (WITHOUT/WITH SPACE)
* [brackets]  (WITHOUT/WITH SPACE)
* {braces}  (WITHOUT/WITH SPACE) 
* "quotes"
* *stars*
* -hyphen-
* |pipe|
* @at@
* #octothop#
* &apersand&
* <tag>tag</tag>
```

### > NORMAL MODE

**NOTE:** You can change the last character with any other ***(see the non-exhaustive list above).***

|	COMMANDS	|			EXPLANATION/USAGE				|
|-----------------------|-----------------------------------------------------------------------|
|`yss)`			|surround the **entire line** with where the cursor is WITHOUT SPACE -> `(Welcome to CS)`
|`yss(`			|surround the **entire line** with where the cursor is WITH SPACE -> `( Welcome to CS )`
|			|
|`ysw)`			|surround the actual word where the cursor is WITHOUT SPACE -> `(Welcome)`| 
|`ysw(`			|surround the actual word where the cursor is WITH SPACE    -> `( Welcome )`|
|`ysiw)`		|surround the actual word WITHOUT SPACE -> `(Welcome)`
|`ysiw(`		|surround the actual word WITH SPACE -> `( Welcome )`
|`ys2w{`		|surround the 2 next words WITHOUT SPACE -> `{Welcome to}`
|`ys2w}`		|surround the 2 next words WITH SPACE -> `{ Welcome to }`
|`ys2aw{`		|surround the 2 next words with the blank WITHOUT SPACE -> `{Welcome to}`
|`ys2aw}`		|surround the 2 next words with the blank WITH SPACE -> `{ Welcome to }`
|`ySS` or `ySs`		|surround the **entire line**, place it on a new line & indent
|`2ySS` or `2ySs`	|surround all of the line (like paragraph), place it on a new line & indent
|			|
|`cit`			|change inside tag -> `<code></code>`
|`cs"'`			|change surround from `"` to `'` -> `"Welcome"` -> `'Welcome'`
