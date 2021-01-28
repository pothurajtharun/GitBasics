# GitBasics
This is to practice git commands.

#To remove remote commit in a branch (tharun)
1. git rebase -i HEAD~(no of commits to remove.)
Ex: git rebase -i HEAD~1
2. It will open a rebase editor. Press ESC key and enter ":wq" and click enter.
3. git log (To check the commits are removed or not).
4. git push origin +branch name.
Ex: git push origin +tharun



