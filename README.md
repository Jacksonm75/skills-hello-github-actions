<header>

[English](https://github.com/skills/hello-github-actions) | 中文

> 本课程翻译自 Github Skills，全部课程请点击 [这里查看](https://www.github-zh.com/getting-started)

# Hello GitHub Actions

_学习如何创建并运行一个 GitHub Actions 工作流(Workflow)。_

</header>

## Step 5: 触发工作流

_现在你的仓库里已经有一个可以正常运行的工作流程了! :smile:_

接下来，我们来运行它，看看效果。

这个工作流程里的 shell 脚本会在**每当有人新建一个 pull request 时**自动执行。

**如何查看工作流程是否触发？** 当 pull request 被创建后，GitHub 会自动运行对应的 workflow。在 PR 页面中，你可以看到它的执行状态。如果看到 **All checks have passed**，说明运行成功。

你也可以打开仓库里的 **Actions** 标签页，查看所有运行中的或已完成的 workflow。在那里还能点开某次运行，查看详情和日志。

![Actions 页面中显示 workflow 运行列表的截图](https://user-images.githubusercontent.com/16547949/62388049-4e64e600-b52a-11e9-8bf5-db0c5452360f.png)

### :keyboard: 实操环节: 触发工作流

1. 创建一个名为 `test-workflow` 的新分支。
2. 修改任意文件，比如在 README.md 里加一个 emoji，然后直接提交到这个新分支。
3. 打开 **Pull requests** 标签页，创建一个从 `test-workflow` 合并到 `main` 的 pull request。
4. 查看 PR 页面中的检查（checks）区域，观察 workflow 的运行。
5. 注意工作流自动在该 pull request 下添加的评论。
6. 等待大约20秒，然后刷新当前课程页面。[GitHub Actions](https://docs.github.com/en/actions) 会自动检测并进入下一步。

<footer>

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/hello-github-actions) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
