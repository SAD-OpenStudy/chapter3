"#yuquan's Git Learning Notes" 
**第一次实验总结**
git add：把工作区的修改添加到暂存区（ staging area ），告诉 Git 准备记录这次修改。
可以 git add 文件名 只加某个文件，也可以 git add . 加全部。

git：把暂存区的修改正式提交到本地仓库，生成一个版本记录，附带提交说明。
只有 commit 后，修改才真正在本地仓库里存了一个版本快照。

git restore：撤销工作区还没 add 的修改（git restore 文件名），把文件恢复到最近一次 commit 的状态。
如果已经 add 了，需要 git restore --staged 文件名 先撤出暂存区。

commit 和 push 的区别：
- commit：只把修改保存到你**本地**的 Git 仓库，别人看不到。
- push：把你本地 commit 的内容**上传到远程仓库**（比如 Gitee），别人才能看到和下载。