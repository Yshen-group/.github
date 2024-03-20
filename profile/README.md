## Hi！👋 沈组小分队的小伙伴们 

### 🙋‍♀️ A short introduction

本仓库是为了传承**沈组代码**而创建的，旨在利用 Git 版本管理系统来**促进组内团队协作和代码管理**，同时建立 Github Private Repo 来保证** online 办公时的远程代码获取**。在使用的过程中请您注意一下要点：

1. 鼓励使用不同 repo 来管理不同的项目，建议命名为“proj_$name”，如 “proj_jdbus”，同时建议复制 template repo。
2. 请保留数据样本以保证它人可以运行代码，完整的数据请勿上传至 git，请存储于 NAS 路径为 STEP-TeamProject”

### 👩‍💻 How to get start
1️⃣ 首先，确保你的电脑已经安装好 git 并配置好 github 仓库。

2️⃣ 然后克隆对应仓库到您本地机器上
```
git clone https://github.com/chenxia31/Group_shen.git
```
3️⃣ 在进行任何更改之前，请始终确保你的本地仓库是最新的
```
git pull origin main
```
4️⃣ 为了确保项目的组织性和可维护性，请您遵循以下步骤创建和使用分支：
<details>

<summary> 从创建代码到PR 流程 </summary>

1. 创建分支：基于新建项目或者开发的功能或版本
   ```
   git checkout -b <branch-name> # 请使用具有描述性的分支名称，如 add_timetable_sim#02
   ```
2. 提交更改：在你的分支上进行更改之后，使用一下命令来添加更改到暂存区并提交它们
   ```
   git add .
   git commit -m 'Add a descriptive commit message'
   ```
3. 推送分支：将您的分支推送到远程仓库
   ```
   git push origin <branch-name>
   ```
4. 创建 PR：在 github 上为你的分支创建一个 Pull request，请求团队成员进行代码审查，一旦审查通过并且没有冲突，可以将你的分支合并到对应的项目分支

</details>


### 🧐 Useful documents

了解 Git 原理：[Git 原理入门](https://www.ruanyifeng.com/blog/2018/10/git-internals.html)

常用 Git 命令：[Git 常用指令](https://www.ruanyifeng.com/blog/2015/12/git-cheat-sheet.html)

希望深入学习 Git：[Pro git book](https://git-scm.com/book/zh/v2)

跟着动画学习 Git：[Welcome to Learn Git Branching](https://learngitbranching.js.org/)

### 🍿 Fun facts
[Github 组织说明](https://docs.github.com/zh/organizations)

🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
