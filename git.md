![gitlogo](https://i.imgur.com/DrdxJxr.png)

# GIT CHEAT SHEET

* This markdown file was entirely done with the VIM EDITOR & the commands bellow.
* All of images used was resize with [Resizeimage.net](http://resizeimage.net/ "website for resizing image") & upload to [Imgur.com](http://imgur.com "website for uploading image")

---

## MAKE REPO

first you need file for init repo, in this example i made a README.md

```
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:rztprog/repotest.git
git push -u origin master
```

## SOME COMMANDS

|         COMMANDS		|			EXPLANATION/USAGE				|		EXTRA		|
|-------------------------------|-----------------------------------------------------------------------|-------------------------------|
| git init			| to initialize a directory with git
| git status			| show the staged
| git add			| git add file1.md to add file1.md to the staged	| replace the file1.md  by "." for adding all of the file
| git commit 			| git commit -m "message"
| git branch			| git branche branch1 to create the branch1		| "git branch" without paramater show all branches
| git checkout			| git checkout branch1 to switch in branch1 		| similar of CD command in terminal
|				|
| git log			| show the commit(s)					| "git log -n 3" to show the 3 last commits
| git pull			| pull all of the repo					| 
| git push			| push you work on the repo				| git push -u origin master (for the first push)
|				|
| git remote add origin "url"	| create a tunnel between your directory & the repo
