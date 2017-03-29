# Git commit 注释规范

## 提交格式：
````
<type>(<scope>): <subject>
// 空一行
<body>
````

> 建议使用````git commit -v````方法提交
> 日常开发代码请一律提交至develop（开发）分支，后期codeReview后一起合并至master分支。

## 范例:
````
fix: feat(0429留言下单): add 'graphiteWidth' option

提交的具体情况
````


## 说明：
> type（必需）、scope（可选）和subject（必需）。

> body(可选)

### (1) type
* type用于说明 commit 的类别，只允许使用下面8个标识。
* br: 此项特别针对bug号，用于向测试反馈bug列表的bug修改情况
* feat：新功能（feature）
* fix：修补bug
* docs：文档（documentation）
* style： 格式（不影响代码运行的变动）
* refactor：重构（即不是新增功能，也不是修改bug的代码变动）
* test：增加测试
* chore：构建过程或辅助工具的变动
* revert: feat(pencil): add 'graphiteWidth' option (撤销之前的commit)

### (2)scope
scope用于说明 commit 影响的范围，比如数据层、控制层、视图层等等，视项目不同而不同。

### (3)subject
subject是 commit 目的的简短描述，不超过50个字符。
以动词开头，使用第一人称现在时，比如change，而不是changed或changes
第一个字母小写
结尾不加句号（.）

### (4)body
Body 部分是对本次 commit 的详细描述，可以分成多行。