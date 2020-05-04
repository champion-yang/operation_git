# operation_git
git 操作
1. `git clone 远程地址`   把远程项目克隆到本地 比如说项目文件名叫 "test" 则本地会生成一个名为"test" 的文件夹，里面有 .git  和 一个 README.md 的文件。
2. `cd test` 进入项目文件夹，开始新建文件(比如 .html .css 的文件) 或者在原有文件的基础上进行修改。此时可以使用 `git status` 查看当前文件的状态。文件是红色的。若当前功能模块已经开发完成，则进行 `git add *` 添加。
3. `git add *` 把所有的文件放在暂存区 ，再次使用 `git status` 查看当前文件的状态。文件是绿色的
4. `git commit -m '描述内容'` 对本次的提交做一个描述. 内容可以包括本次进行修改的功能性描述。此时使用 `git log` 可以看到本次的提交信息。
5. `git push origin master` 把本地仓库的代码推送到远程仓库。origin master 代表远程的master 分支。

## 创建新分支进行提交
git branch xxx 创建新分支xxx
git checkout xxx 切换到分支xxx

## 使本地仓库的代码和远程仓库的代码保持一致
`git pull`