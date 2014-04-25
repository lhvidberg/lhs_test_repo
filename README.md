-- first repo commands
git config --global user.name "Lars Hvidberg"
git config --global user.email "lars@xlh.dk"
git config --list
exit
cd h:
cd data
cd lars
cd coursera/
cd DataScienceSpecialization/
mkdir git
cd git/
mkdir test
cd test/
touch README.md
git init
git add README.md
commit -m "first commit"
git commit -m "first commit"
git remote add origin https://github.com/lhvidberg/lhs_test_repo.git
git push -u origin master

