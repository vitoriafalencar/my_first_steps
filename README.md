01

https://github.com/vitoriafalencar/my_first_steps.git

02

$ git init
Initialized empty Git repository in C:/Users/Mariana/Desktop/Diretório git/.git/

Mariana@DESKTOP-HI3H45A MINGW64 ~/Desktop/Diretório git (master)
$ git branch  -M main

Mariana@DESKTOP-HI3H45A MINGW64 ~/Desktop/Diretório git (main)
$ git remote add origin https://github.com/vitoriafalencar/my_first_steps.git

Mariana@DESKTOP-HI3H45A MINGW64 ~/Desktop/Diretório git (main)
$

03

$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ola_mundo.txt

nothing added to commit but untracked files present (use "git add" to track)

Mariana@DESKTOP-HI3H45A MINGW64 ~/Desktop/Diretório git (main)
$ git add ola_mundo.txt

Mariana@DESKTOP-HI3H45A MINGW64 ~/Desktop/Diretório git (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   ola_mundo.txt


Mariana@DESKTOP-HI3H45A MINGW64 ~/Desktop/Diretório git (main)
$ git commit -m "primeiro commit"
[main (root-commit) dd452e7] primeiro commit
 1 file changed, 1 insertion(+)
 create mode 100644 ola_mundo.txt

Mariana@DESKTOP-HI3H45A MINGW64 ~/Desktop/Diretório git (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 256 bytes | 64.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/vitoriafalencar/my_first_steps.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

Mariana@DESKTOP-HI3H45A MINGW64 ~/Desktop/Diretório git (main)
$

04

Mariana@DESKTOP-HI3H45A MINGW64 ~/Desktop/Diretório git (main)
$ touch .gitignore

Mariana@DESKTOP-HI3H45A MINGW64 ~/Desktop/Diretório git (main)
$ touch serei_ignorado.txt

Mariana@DESKTOP-HI3H45A MINGW64 ~/Desktop/Diretório git (main)
$ notepad

Mariana@DESKTOP-HI3H45A MINGW64 ~/Desktop/Diretório git (main)
$ notepad serei_ignorado.txt

Mariana@DESKTOP-HI3H45A MINGW64 ~/Desktop/Diretório git (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore
        serei_ignorado.txt
        "\342\200\234.gitignore\342\200\235.txt"

nothing added to commit but untracked files present (use "git add" to track)

Mariana@DESKTOP-HI3H45A MINGW64 ~/Desktop/Diretório git (main)
$ notepad .gitignore

Mariana@DESKTOP-HI3H45A MINGW64 ~/Desktop/Diretório git (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore
        "\342\200\234.gitignore\342\200\235.txt"

nothing added to commit but untracked files present (use "git add" to track)

Mariana@DESKTOP-HI3H45A MINGW64 ~/Desktop/Diretório git (main)
$
