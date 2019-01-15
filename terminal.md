![terminallogo](https://i.imgur.com/LNgtd7k.png) 

# TERMINAL CHEAT SHEET

* This markdown file was entirely done with the VIM EDITOR & the commands bellow.
* All of images used was resize with [Resizeimage.net](http://resizeimage.net/ "website for resizing image") & upload to [Imgur.com](http://imgur.com "website for uploading image")

---

## SOME SHORCUTS 

|         SHORTCUTS             |                       EXPLANATION/USAGE                               |
|-------------------------------|-----------------------------------------------------------------------|
| [ALT + TAB]			| Switch between last Ubuntu window					
| [CTRL + ALT + ARROW-UP/DOWN]	| Switch between the Ubuntu windows
|				|	
| [CTRL + ALT + T]		| Open a new terminal window
| [CTRL + C] 			| Stopping script
| [CTRL + SHIFT + T] 		| Open a new terminal tab
| [CTRL + SHIFT + W]		| Close the active terminal tab
| [CTRL + UP/DOWN]		| Change the terminal TAB (Up to go  forward) (Down to go backward)
| [CTRL + SHIFT + UP/DOWN]	| Move the TAB
| [CTRL + SHIFT + C]		| Copy the text
| [CTRL + SHIFT + V]		| Paste the text
| [CTRL + L]			| Clear

## SOME COMMANDS

|         COMMANDS		|                       EXPLANATION/USAGE                               |              EXTRA              |
|-------------------------------|-----------------------------------------------------------------------|---------------------------------|
| cd (change directory) 	| cd pictures (change to the picture directory)				| cd without nothing to go in ~home
| ls (show folder & file) 	| ls (juste type without nothing) 					| ls -la (show invisible (.) folder & file) 
| pwd (show the current folder)	| pwd (just type withouh nothing)
| mkdir (make directory)	| mkdir directory1 (create the directory directory1) 
| rmdir (rm directoryi)		| rmdir directory1 (remove the directory directory1)			| (the dir need to be empty)
| mv (move or rename)		| mv file1 file2 (rename the file1 in file2)
| touch (create empty file)	| touch file1 (create an empty file named file1)	
| vi (open vim editor)		| vi file1 (open the file1 in the vim text editor) 
| sudo				| run command in super user (admin)
| apt-get			| get an application from the librairie software
| install			| install an application you just download
| sudo apt-get update		| download the package lists from the repos
| sudo apt-get upgrade		| fetch new versions of existing packages
| sudo apt-get disk-upgrade	| update the kernel

## SOME SELF USEFULL ALIASES

|		ALIASES				|		COMMANDS			|
|-----------------------------------------------|-----------------------------------------------|
| tt						|	watch -n1 "date +%n%T|figlet -k"	|	
| cdt						|	figlet Welcome to the RZT WORLD		|
| agu						|	sudo apt-get update			|
| agi						|	sudo apt-get upgrade			|
| ago						|	sudo apt-get dist-upgrade		|
| inst						|	sudo apt-get install			|
| remo						|	sudo apt-get remove			|
| rema						|	snap remove				|
| baba						|	vi ~/.bashrc				|
| vivi						|	vi ~/.vimrc				|
|						|						|
| ginit						|	git init				|
| gchk						|	git checkout				|
| gsta						|	git status				|
| gadd						|	git add	+ FILE				|
| gpull						|	git pull				|
| gpush						|	git push				|
| gcom						|	git commit -m + "MESSAGE"		|
| glog						|	git log	-n + "NUMBER"			|
| gbra						|	git branch + "BRANCH NAME"		|
| gtun						|	git remote -v (see the tunnel link)	|
