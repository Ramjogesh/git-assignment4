# git-assignment4


Below Commands are user for this assignments.


cd git-assignment4
touch master.txt
ls
git status
git add .
git commit -m "added master.txt file"
git push origin main
git checkout -b public1
git checkout -b public2
git checkout -b private
git checkout public1
touch public1.txt
git add .
git commit -m "added public.txt file"
git push origin
git push --set-upstream origin public1
git checkout main
git merge public1
git merge public2
git checkout public2
cat master.txt
git merge public2
git checkout private
vim master.txt
git status
cat master.txt
git add .
git commit -m "update master file"
git checkout public1
git merge main
git checkout public2
git merge main
git checkout main
git merge private
git merge main
