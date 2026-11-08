git clone https://github.com/oomeva/indwork1.git indwork1
Cloning into 'indwork1'...
warning: You appear to have cloned an empty repository.

oomeva@oomeva-ROG-Strix-G731GU-GL731GU:~/Documents/TP/lab1$ cd indwork1

oomeva@oomeva-ROG-Strix-G731GU-GL731GU:~/Documents/TP/lab1/indwork1$ git remote -v
origin	https://github.com/oomeva/indwork1.git (fetch)
origin	https://github.com/oomeva/indwork1.git (push)

oomeva@oomeva-ROG-Strix-G731GU-GL731GU:~/Documents/TP/lab1/indwork1$ git status
On branch main

No commits yet

nothing to commit (create/copy files and use "git add" to track)

oomeva@oomeva-ROG-Strix-G731GU-GL731GU:~/Documents/TP/lab1/indwork1$ touch readme.txt

oomeva@oomeva-ROG-Strix-G731GU-GL731GU:~/Documents/TP/lab1/indwork1$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	readme.txt

nothing added to commit but untracked files present (use "git add" to track)

oomeva@oomeva-ROG-Strix-G731GU-GL731GU:~/Documents/TP/lab1/indwork1$ git add readme.txt

oomeva@oomeva-ROG-Strix-G731GU-GL731GU:~/Documents/TP/lab1/indwork1$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   readme.txt

oomeva@oomeva-ROG-Strix-G731GU-GL731GU:~/Documents/TP/lab1/indwork1$ git commit -m "Связал репозитории"
[main (root-commit) d5e164c] Связал репозитории
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 readme.txt

oomeva@oomeva-ROG-Strix-G731GU-GL731GU:~/Documents/TP/lab1/indwork1$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

nothing to commit, working tree clean

oomeva@oomeva-ROG-Strix-G731GU-GL731GU:~/Documents/TP/lab1/indwork1$ git remote -v
origin	https://github.com/oomeva/indwork1.git (fetch)
origin	https://github.com/oomeva/indwork1.git (push)

oomeva@oomeva-ROG-Strix-G731GU-GL731GU:~/Documents/TP/lab1/indwork1$ git push
Username for 'https://github.com': oomeva
Password for 'https://oomeva@github.com': 
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 258 bytes | 258.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/oomeva/indwork1.git
 * [new branch]      main -> main

oomeva@oomeva-ROG-Strix-G731GU-GL731GU:~/Documents/TP/lab1/indwork1$ git remote -v
origin	https://github.com/oomeva/indwork1.git (fetch)
origin	https://github.com/oomeva/indwork1.git (push)
oomeva@oomeva-ROG-Strix-G731GU-GL731GU:~/Documents/TP/lab1/indwork1$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

oomeva@oomeva-ROG-Strix-G731GU-GL731GU:~/Documents/TP/lab1/indwork1$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

oomeva@oomeva-ROG-Strix-G731GU-GL731GU:~/Documents/TP/lab1/indwork1$ git remote -v
origin	https://github.com/oomeva/indwork1.git (fetch)
origin	https://github.com/oomeva/indwork1.git (push)

