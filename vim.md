![vimlogo](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9f/Vimlogo.svg/220px-Vimlogo.svg.png)

# VIM CHEAT SHEET

* This markdown file was entirely done with the **VIM EDITOR** & the commands below.
* All of images used was resize with [Resizeimage.net](http://resizeimage.net/ "website for resizing image") & upload to [Imgur.com](http://imgur.com "website for uploading image")

---

## SOME SHORTCUTS  

### > NORMAL MODE - SHORTCUTS

|	  SHORTCUTS		| 			EXPLANATION/USAGE				| 	       EXTRA		  |
|-------------------------------|-----------------------------------------------------------------------|---------------------------------|
|h				| cursor go LEFT							| 2h (move 2 time left)
|j				| cursor go DOWN							| 4j (move 4 time down)
|k				| cursor go UP								| 3k (move 3 time up)
|l				| cursor go RIGHT							| 7l (move 7 time right)
|				|
|dd				| delete the line on the cursor & keep in the buffer			| ddp (cut & past next line)
|D				| delete the text from the cursor & keep in the buffer 			| 3D (delete the 3 next line from the cursor)
|s				| delete a letter & enter in INSERT MODE
|S				| delete the text on the line & enter in INSERT MODE
|x 				| delete letter on the cursor & keep in the buffer			| xp (cut & past)
|X				| delete the previous word & keep in the buffer				| 4X (delete 4 previous word & keep in buffer)
|dw				| delete 1 word from the cursor						| d3w (delete 3 next word)
|cw 				| delete 1 word from the cursor & enter in INSERT MODE			| c4w (rewrite 4 new word) 
|C				|
|				|
|H				| move to the TOP of the actuel window position
|M				| move to the MIDDLE of the actual window position
|L				| move to the LOW of the actual window position
|				|
|gg				| move to the top of the file
|G				| move to the down of the file
|15G				| move at the line 15 (change the number to move in another line)	| same to :15 (but withouh ENTER) 
|b				| move at the beginning of the previous word
|B				| move at the beginning of the previous WORD
|e				| move at the end of the next word
|E				| move at the end of the next WORD
|w				| move at the beginning of the next word				| 3w (move to the beginning of next 3rd word)
|W				| move at the beginning of the next WORD
|$				| move at the end of the line
|0				| move at the beginning of the line
|^ (ALTGr + 9)			| move at the first word on the line
|				|
|i 				| enter in INSERT MODE on the cursor
|I				| enter in INSERT MODE at the beginning of the line
|a				| enter in INSERT MODE after the cursor
|A				| enter in INSERT MODE at the end of the line after the cursor
|o				| enter in INSERT MODE on the next line
|O				| enter in INSERT MODE on the previous line
|				|
|J				| bring back the next ligne						| 4J (bring back 3 next line)
|yyp				| yank yank & paste (copy in the buffer & paste)
|r				| replace the letter/number on the cursor
|R				| replace all of the text beginning on the cursor
|u				| undo the last command
|U				| undo the last action
|				|
|~ (ALTGr + 2)			| uppercase a letter
|. 				| do the previous command
|/"letter"			| /f -> search next "f" (ENTER to go there)
|?"letter"			| ?a -> search previous "a" (ENTER to go there)
|%				| move to matching caracter, defaut supported "()", "{}", "[]"
|				|
|ENTER				| go down 1 time (like "1k" or "k")
|ZZ				| save current file & quit (like :wq!)
|ZQ				| quit without saving (like :q!)
|				|
|gg=G				| Indent perfectly the page

### > VISUAL MOD SHORTCUTS

|	  SHORTCUTS		| 			EXPLANATION/USAGE				| 	       EXTRA		  |
|-------------------------------|-----------------------------------------------------------------------|---------------------------------|
|v				| enter in VISUAL MODE
|V				| enter in V-LINE (highlight the entire line)
|y (yank/copy)			| copy (in the buffer) the text or the word
|p				| paste the text on the cursor



## SOME COMMANDS 

|	  COMMANDS		| 			EXPLANATION/USAGE				| 	       EXTRA		  |
|-------------------------------|-----------------------------------------------------------------------|---------------------------------|
|[CTRL+T]			| add a tabulation from the start of the actual line
|				|
|:w				| save the file 							| forcing command with "!" (:wq!)
|:q				| quit the file								| forcing command with "!" (:wq!)
|:wq				| save & quit the file							| forcing command with "!" (:wq!)
|:15				| move to line 15							| same to 15G (but with ENTER)
|				|
|:r "fichier"			| copy & past all of the file under the actual file
|:nohlsearch			| cancel the highlited text
|				|
|:PlugInstall			| open vimplug installer
|:PlugClean			| to cleanup vimplug when a plugin is removed
|				|
|:s (search)			| you can do some tricks with ":s" like replacing some word/WORD by adding slash "/" -> exemple -> :s/word1/word2/g. if you want to replace all occurencies add a % before s -> exemple -> :%s/word1/word2/g | More information : [vim.wikia.com] (http://vim.wikia.com/wiki/Search_and_replace)
|:vsp				| virtual split								| [CTRL+ww] for switch
