# Program3
mkdir Git3
cd Git3
git init
echo "line1" >> file.txt
echo "line2" >> file.txt
git add .
git commit -m "initial commit"
git checkout -b branch-a
echo "change from branch A" >> file.txt
git commit -m "edit from branch A"
git checkout branchname
got checkout -b branch-b
echo "change from branch B" >> file.txt
git commit -m "edit from branch B"
git add .
git commit -m "Final commit"
