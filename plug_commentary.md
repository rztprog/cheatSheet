![kyle_southpark_logo.gif](https://media.giphy.com/media/xTdy8n1oLK2clXista/giphy.gif)

# COMMENTARY PLUGIN CHEAT SHEET

* This markdown file was entirely done with the **VIM EDITOR** & the commands below.
* All of images used was resize with [Resizeimage.net](http://resizeimage.net/ "website for resizing image") & upload to [Imgur.com](http://imgur.com "website for uploading image")
* Gif was take with [Peek](https://github.com/phw/peek) PPA

## INSTALL-IT VIA [GITHUB](https://github.com/tpope/vim-commentary) OR [VIMAWESOME](https://vimawesome.com/plugin/commentary-vim)

**NOTE:** If your ***favorite file type isn't supported***, type this ***command below*** (you need to adjust ***commentstring***)

```
autocmd FileType apache setlocal commentstring=#\ %s
```

---

## EXEMPLES

#### MARKDOWN (.md) FILE

![markdown_file_exemple.gif](https://i.imgur.com/mOuutGF.gif)

Command: `gcc`

#### HTML (.html) FILE

![html_file_exemple.gif](https://i.imgur.com/CJUEjKj.gif)

Command: `2gcc`

---

## SOME COMMANDS

### > NORMAL MODE

|	COMMANDS	|			EXPLANATION/USAGE				|		EXTRA		|
|-----------------------|-----------------------------------------------------------------------|-------------------------------|
|`gcc`			| comment entire line							| `2gcc` to comment 2 lines	|
|`gcap`			| comment the paragraph (the block)					| `3gcap` to comment 3 blocks	|


### > VISUAL MODE

|	COMMANDS	|			EXPLANATION/USAGE				|
|-----------------------|-----------------------------------------------------------------------|
|`gc`			| highlight what you want and type `gc` for comment			|

### > COMMAND MOD

|	COMMANDS	|			EXPLANATION/USAGE				|
|-----------------------|-----------------------------------------------------------------------|
|`:20,25Commentary`	| comment from line 20 to 25						|
|`:g/COMMANDS/Commentary`| target all of lines who contain `COMMANDS` & commented them		|

