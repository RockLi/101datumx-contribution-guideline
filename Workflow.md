

# 项目管理

项目使用 [Trello](https://trello.com) + [Scrum](https://www.scrum.org/resources/what-is-scrum) 的方式进行开发管理

请先注册 Trello 帐号 以及 安装 [Scrum for Trello Extension](https://trello.com/c/RyF66ESX/8-scrum-for-trello)

每个 Task 都会预先定义好输入、输出，以及粗略的耗时，针对 Task 的沟通请使用 Trello 的 Comment 功能。


# 代码管理

项目使用 Git 并托管在 Github 上， 我们对代码的质量看的非常重，请务必在提交代码前做好自测，如若可能，请参加测试代码。

如代码经常通不过 Code Review，或者 BUG 数相对较多，会直接影响到你对项目的贡献度。

## 开发流程

1. 在 TODO 列的代表是可工作的 Task, 任务优先级从上往下依次降低
2. 在开发的时候把 Task 从 TODO 列拖到 Doing 列，并把 Task Assign 给自己，如有任何问题，需及时的在 Task 加上 comment，并通过即时聊天咨询
3. 任务做完后，把 Task 拖到 Code Review 列，等待 Code Review，并附上PR链接
4. 只有 Task 经过 Code Review 并拖动到Done 列才代表一个任务真正的完成, 有可能会出现 Task 在 Doing 和 Code Review 列来回移动

## 代码规范

1. 前端 Javascript 代码规范, [Google](https://google.github.io/styleguide/jsguide.html)
2. 后端 Python 代码规范, [pep8](https://www.python.org/dev/peps/pep-0008/), [Google](https://google.github.io/styleguide/pyguide.html)
3. 后端 Go 代码规范 [Go](https://github.com/golang/go/wiki/CodeReviewComments)

## Git相关规范

1. 不要用一个大 Commit 提交所有的工作，尽量将 Commit 切分成多个小 Commit
2. Github 上PR的名字要描述的精确， 在描述内容里尽量描述本次提交的内容
3. Task上应该附录上具体的 PR 链接，供 Code Reviewer 进行  Review


