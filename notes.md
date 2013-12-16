# Notes

- Diff created in 1970, http://en.wikipedia.org/wiki/Diff

- SCCS, 1972

- RCS, 1982, better format than SCCS

- Patch built on diff, 1985 (Larry Wall of Perl Fame)

- CVS, 1986 (on top of RCS)

- SVN, 2000, modern successor to CVS

- CVS and SVN had problems with larger teams + you couldn't work on the train

- Proliferation of "Distributed Source Control Tools", GNU arch (then baz and then bazaar)

- Linux used BitKeeper (which derived from Sun TeamWare, built on SCCS + NFS) until there was a license fall out

- Linus wrote Git (coincidentally another kernel developer wrote Mercurial)

# My Notes

git clone https://github.com/PyLadiesDublin/git-tutorial.git

.md files, stuff you're working on, workpath
add changes you want to make to the index/staging area
commit, to actually save, to local copy of repo
origin, clone from, push to

git status

edit file

git add filename (to staging)

git commit (to local)
git commit -m "commit message"

git log
git diff

git config --list

git config --global user.email user@example.com
git config --global user.name "name"

git push (see later)

... crashed ...

fork in webpage, copy link

https keeps prompting for passwords
change preferance to ssh (can set up to remember password)

ssh-keygen

git remote set-url origin copied-link

git push origin master

pull request - ask forked repo to pull/take changes from me


git pull (pull updates from the origin)

git remote -v

git remote pyladies link
