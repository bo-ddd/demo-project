### READEME.md

1. 这是一个学习git的demo项目;

在你刚拉完项目后
你本地只有一个master分支
你根本就没有Dev_br20220720分支，
1.你需要在本地创建一个分支
2.你的分支要和线上进行关联,
关联的意思是,你创建的分支要从哪个分支上代码拉过来,你提交的代码要提交到哪个线上分支上;
3. 你想在这个分支上开发,
你得切换到这个分支

git checkout -b  Dev_br20220720  origin/Dev_br20220720

-b : 分支    创建分支
git checkout  切换分支
origin/Dev_br20220720 所要关联的分支；

凡是带有 origin/branchName  这种就是远程分支 
凡是 不带的  branchName  就是本地分支