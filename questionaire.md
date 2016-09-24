Q1: If I clone from the https addr, will I get all the branhes? 
A： It seems that I have all the branches, and I can use "git checkout" to switch to that branch. But when using "git branch", I can see only one branch "master"

Q2：What is upsteam?
$git remote -v
origin    https://github.com/YOUR_USERNAME/YOUR_FORK.git (fetch)
origin    https://github.com/YOUR_USERNAME/YOUR_FORK.git (push)
upstream  https://github.com/ORIGINAL_OWNER/ORIGINAL_REPOSITORY.git (fetch)
upstream  https://github.com/ORIGINAL_OWNER/ORIGINAL_REPOSITORY.git (push

Q3: How to summit to the remote reposit?
A: Please refer to http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/001374385852170d9c7adf13c30429b9660d0eb689dd43a000

Q4: add SSH to gitHub
A: https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/#adding-your-ssh-key-to-the-ssh-agent

Q5:当要ｐｕｓｈ的时候，是否只能ｐｕｓｈ当前分支
Ａ：ＮＯ

Q6: If we add a file to the staged repo, how can we delelet it from the repo?
A: Use  "git rm filenam"

Q7: If we have added a file A to the sraged repo and we accidentallly delete it from our working dir, how can we recovery the file?
A: Uses "git chekcout -- filename"
