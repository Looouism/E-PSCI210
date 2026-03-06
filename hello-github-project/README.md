# Hello GitHub 项目（入门版）

这是一个给初学者准备的示例项目，用来理解 GitHub 的核心构成。

## 1. Repository（仓库）是什么？

`Repository`（简称 repo）就是一个项目的“总文件夹 + 历史记录系统”。

在一个仓库里，你通常会放：
- 代码（`src/`）
- 文档（`docs/`、`README.md`）
- 配置文件（如 `.gitignore`）
- 版本历史（由 Git 自动记录）

你现在看到的这个目录本身，就是一个 Git 仓库。

---

## 2. 本示例项目结构

```text
hello-github-project/
├── README.md
├── src/
│   └── main.py
└── docs/
    └── github-basics.md
```

每个部分的作用：
- `README.md`：项目首页说明（别人打开仓库最先看到）
- `src/main.py`：示例代码
- `docs/github-basics.md`：更详细的 GitHub 概念讲解

---

## 3. GitHub 的核心构成（你最需要先懂这些）

1. **Repository（仓库）**
   - 存放项目文件与历史版本。

2. **Commit（提交）**
   - 每次保存一次变更，都会形成一个 commit。
   - 可以理解成“项目快照 + 说明文字”。

3. **Branch（分支）**
   - 默认分支常见是 `main`。
   - 你可以开新分支做功能，不影响主线，做完再合并。

4. **Pull Request（PR）**
   - 把“某个分支的改动”提交给团队审核并合并。
   - 通常用于协作开发。

5. **Issue（问题单）**
   - 记录 bug、需求、任务。
   - 相当于项目的待办事项系统。

6. **Actions（自动化）**
   - 自动运行测试、构建、部署等流程。

---

## 4. 你可以怎么开始用 GitHub（最小流程）

1. 创建仓库
2. 添加文件并提交（commit）
3. 推送到 GitHub
4. 修改代码继续提交
5. 若多人协作：开分支 + 提 PR

---

## 5. 一句话总结

- **Git** 负责“版本管理”（本地）
- **GitHub** 负责“托管 + 协作平台”（云端）
- **Repository** 就是你项目的家，记录了“现在有什么”以及“过去怎么变成现在”
