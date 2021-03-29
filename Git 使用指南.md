## Git 使用指南

* 分布式版本管理系统，仅限文本文档的跟踪，其他格式可以被管理，但不能跟踪修改的具体信息，比如word就不行，它是二进制文档。采用notepad等编辑器即可。
* 进入一个目录，`git init`可以把这个目录变成可管理的仓库，出现.git目录
* `git add`把文件添加到仓库
* `git commit -m "some explaination about the commit"`把文件提交到仓库
* `git status` 查看系统状态，显示有没有修改，有没有待添加待提交的文件
* `git diff`查看修改的具体内容， 修改了但还没有添加提交
* 