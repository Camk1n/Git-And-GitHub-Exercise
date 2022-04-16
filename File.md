git init<br>
git add File.md <br>
git commit -m "Commit 0" <br>
git add File.md <br>
git commit -m "Commit 1" <br>
git add File.md <br>
git commit -m "Commit 2" <br>
git log <br>
git checkout 6fbdc25299f4568e59a03f98e67abb555508827b <br>
git branch Fristbranch <br>
git checkout Fristbranch <br>
git add File.md <br>
git commit -m "Commit 3" <br>
git add File.md <br>
git commit -m "Commit 4" <br>
git checkout master <br>
<<<<<<< HEAD
git merge Fristbranch <br>
=======
git merge Fristbranch "Commit 5" <br>
>>>>>>> ThirdBranch
git add File.md <br>
git commit -m "Commit 5" <br>
git add File.md <br>
git commit -m "Commit 6" <br>
git checkout 6a0bf6589d13ed1e5f104645f004007f7556a99f <br>
git branch SecondBranch <br>
git checkout SecondBranch <br>
git add File.md <br>
git commit -m "Commit 7" <br>
git add File.md <br>
git commit -m "Commit 8" <br>
git add File.md <br>
git commit -m "Commit 9" <br>
git checkout master <br>
git checkout 9e91b59e845a07a6defa716be7081f7101040227 <br>
git add File.md <br>
<<<<<<< HEAD
git commit -m "Commit 10" <br>
git checkout master <br>
git merge SecondBranch <br>
git add File.md <br>
git commit -m "Commit 11" <br>
git add File.md <br>
git commit -m "Commit 12" <br>

=======
git commit -m "Commit 10" <br>
>>>>>>> ThirdBranch
