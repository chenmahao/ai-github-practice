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
