# CICDSample
creating a sample project for 3345
Create a file

Next, you’ll add a new file to this repository.
1.Click the New file button at the top of the Source page.
2.Give the file a filename of contributors.txt.
3.Enter your name in the empty file space.
4.Click Commit and then Commit again in the dialog.
5.Go back to the Source page.

Before you move on, go ahead and explore the repository. You've already seen the Source page, but check out the Commits, Branches, and Settings pages.

commit repository batch file

@echo off

set /p comment=Enter the Comment:

git status

git add .

git commit -m "%comment%"

git push

echo Git Batch Process Complete!

pause
