We don't talk any more. Yes.

Like we used to do. No.

git branch synctest
git add ./
git commit -m "把对某个文件的修改同步到2个分支上，zhyn-2021-03-01"
git checkout synctest
git checkout master -- readme.txt