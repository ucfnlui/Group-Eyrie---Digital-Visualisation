# Group-Eyrie---Digital-Visualisation
It is a repository of Digital Visualisation

## Branch
每个人拉下仓库后，创建自己的分支，并且上传文件到自己的分支里

## 文件
有两个文件夹，一个是Policy Briefing，所有人上传自己的draft；另一个是Reproducible Analysis，有一个iqnb，文件，我注释了从哪里开始编辑自己的代码，大家看清楚自己的代码块

## 关于merge和冲突 （非常重要）
当你完全确定自己的分支可以合并到main后，才可以marge，首先，一定要先git pull后才可以git merge，因为有人可能已经对主支进行了更改
可能会发生conflict，因为别人写的东西会重叠（如果你不写到别人的代码块里，这个情况一般不会发生），确认好conflict后才能上传

## git 指令
养成首先git pull的好习惯，血泪史太多了/(ㄒoㄒ)/~~
当你习惯使用git后，你会发现它很好用

## commit 指令
因为我们是多人合作，所以commit请按照commit规范：
`<type>(<scope>): <subject>`

其中type以及subject为必须要的部分，请注意冒号后的空格，实际使用时不需要"<>", 例如：

`docs(README): fix grammar`

`fix(Main): fix function call`

#### type

用于说明commit的类别，有以下七种

- feat: 新功能，代指feature

- fix: 修补问题bug

- docs: 文档类，如更新readme，模板，会议记录等

- style: 仅改变格式，没有其他影响

- refactor: 重构，不新增，也并非是修改bug

- test: 增加测试

- chore: 构建过程或辅助工具的变动

#### scope（可以省略）

用于说明 commit 影响的范围（暂未清晰）

- 可以是Java 某个类等

#### subject

简单描述具体做了什么

- 动词开头，第一人称单数一般现在时，如add，change
- 首字母小写
- 不加句号


