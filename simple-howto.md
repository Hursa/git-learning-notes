#How to clone a git, checkout to its branch, modify some files and push

git clone git@github.com:Hursa/test.git

git checkout -b dev origon/dev

ddd some files and commit

git push origin dev

#How to new a branch and push it to the remote repo

git checkout -b new_branch_name

do_sth

git push origin new_branch_name


#How to delete local and reomote branch?

LOCAL:

git branch -d <branch_name>

REMOTE:

git branch -a

git push origin --delete <branch_name>

#How to clone OpenWRT from our local GIT server?

git clone server@192.168.1.95:/home/server/Ococci_Git/router/rtk_openwrt_sdk.git

#How to delete a file from a repo?

git rm <filename>

git commit -m "comments"

