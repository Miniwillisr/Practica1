## Documentación GitHub
https://docs.github.com/en

## Escritura basica y formato en MarkDown (Basic writing and formatting syntax)
* https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

## Cheat-Sheet de Git con GitHub
1. https://training.github.com/downloads/github-git-cheat-sheet.pdf <br>
2. https://training.github.com/downloads/github-git-cheat-sheet/


## Quick Setup 
### Quick setup — if you’ve done this kind of thing before or Get started by creating a new file or uploading an existing file.

We recommend every repository include a README, LICENSE, and .gitignore.
![image](https://github.com/Dramzii23/ARQWEB-Repo-01/assets/126987380/1db0ff3f-ffaf-49b6-96a1-e060dbb61f91)

## create a new repository on the command line

```
echo "# TestARQWEB2" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Dramzii23/TestARQWEB2.git
git push -u origin main
```

## ...or push an existing repository from the command line

```
git remote add origin https://github.com/Dramzii23/TestARQWEB2.git
git branch -M main
git push -u origin main
```
