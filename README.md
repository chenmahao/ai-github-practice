# AI GitHub Practice

这个仓库用于练习如何使用 GitHub 和 Codex 进行 AI 辅助编程。

我的目标是借助 Codex 更好地管理和修改 GitHub 项目，而不是独立写代码。
- 管理项目版本
- 让 AI 理解项目
- 让 AI 修改项目
- 检查 AI 改动
- 保存和回退修改


## AI Collaboration Rule

每次让 Codex 修改项目后，我都要先查看 changed files 和 diff，再决定是否 commit。


## Branch Practice

这段内容是在 ai-readme-experiment 分支上添加的，用于练习安全地试验修改。


## Safe Codex Workflow

当我使用 Codex 修改项目时，我会按照这个流程：

1. 先确认当前在 main 分支，并且没有未提交修改
2. 创建一个新的试验分支
3. 让 Codex 先阅读项目，并说明准备修改什么
4. 修改完成后，先查看 changed files 和 diff
5. 确认只改了相关文件，没有奇怪内容
6. 满意后再 commit
7. push 或 publish 分支到 GitHub
8. 创建 Pull Request，并查看 Files changed
9. 合并 Pull Request 后删除分支
10. 回到本地 main，并 pull 最新版本


## Before Codex Edits Checklist

在让 Codex 修改项目之前，我会先检查：

1. 当前分支不是 main，或者我已经准备好创建试验分支
2. GitHub Desktop 显示 No local changes
3. 我已经说明这次要改什么
4. 我已经要求 Codex 先给计划，不要直接修改
5. 我知道修改完成后要检查 changed files 和 diff


## After Codex Edits Review

Codex 修改完成后，我会先检查：

1. GitHub Desktop 里有哪些 changed files
2. 每个文件的 diff 是否符合我的目标
3. 是否只修改了和任务相关的文件
4. 是否出现了我看不懂的大段改动
5. 是否误加入了密码、API key、个人信息或临时文件
6. 是否需要让 Codex 先 review 这次改动，再决定是否 commit
