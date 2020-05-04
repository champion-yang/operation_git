# operation_git
git 操作
1. `git clone 远程地址`   把远程项目克隆到本地 比如说项目文件名叫 "test" 则本地会生成一个名为"test" 的文件夹，里面有 .git  和 一个 README.md 的文件。
2. `cd test` 进入项目文件夹，开始新建文件(比如 .html .css 的文件) 或者在原有文件的基础上进行修改。此时可以使用 `git status` 查看当前文件的状态。文件是红色的。若当前功能模块已经开发完成，则进行 `git add *` 添加。
3.`git add *` 把所有的文件放在暂存区 