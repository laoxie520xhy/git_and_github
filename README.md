# git_and_github

Git 与 GitHub 练习仓库。

## 用途

- 练习 Git 日常操作：add / commit / branch / merge / reset / rebase
- 练习 GitHub 协作流程：远程仓库、push / pull、Pull Request、Issue
- 记录学习笔记与命令备忘

## 目录

| 路径 | 说明 |
| --- | --- |
| `README.md` | 本文件，仓库说明 |
| `.gitignore` | 忽略规则（系统文件、编辑器配置、依赖与构建产物） |

## 常用命令

```bash
# 查看状态与历史
git status
git log --oneline --graph --all

# 日常提交
git add -A
git commit -m "type: 说明"

# 与远程同步
git pull --rebase
git push
```

## 提交信息约定

采用 `type: 描述` 形式，常用 type：

- `feat` 新内容
- `fix` 修正
- `docs` 文档
- `chore` 杂项（初始化、配置）
- `refactor` 重构
