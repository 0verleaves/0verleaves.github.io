# 欢迎来到 GitHub

欢迎来到 GitHub - 在这里，数百万开发者共同协作进行软件开发。准备好开始了吗？让我们通过构建和发布你的第一个 GitHub Pages 网站来了解这一切是如何运作的！

## 代码仓库

现在，我们在你的第一个 GitHub **仓库** 中。一个仓库就像是你项目的文件夹或存储空间。你项目的仓库包含所有文件，如代码、文档、图像等。它还跟踪你（或协作者）对每个文件所做的每一次更改，因此，如果你犯了任何错误，你可以随时返回到项目的以前版本。

这个仓库包含三个重要文件：你的第一个 GitHub 网站的 HTML 代码，用于为你的网站添加颜色和字体的 CSS 样式表，以及 **README** 文件。还有一个包含一个图像文件的图像文件夹。

## 描述你的项目

你正在查看你项目的 **README** 文件。 **_README_** 文件就像是项目的封面或简短介绍。它们以纯文本或 [Markdown 语言](https://guides.github.com/features/mastering-markdown/) 编写，通常包括描述项目、如何使用它的说明、作者是谁等段落。

[了解更多关于 README](https://help.github.com/en/articles/about-readmes)

## 你的第一个网站

**GitHub Pages** 是一种免费且简便的方法，使用存储在你的 GitHub 仓库中的代码来创建网站。你可以使用 GitHub Pages 构建你的作品集，创建个人网站，或者分享你用代码创建的有趣项目。虽然这个仓库中已经自动启用了 GitHub Pages，但是在将来创建新仓库时，启动 GitHub Pages 网站的步骤将会稍有不同。

[了解更多关于 GitHub Pages](https://pages.github.com/)

## 重命名此仓库以发布你的网站

我们已经为你设置好了一个基于你个人用户名的 GitHub Pages 网站。这个仓库被称为 `hello-world`，但你将其重命名为：`username.github.io`，以匹配你网站的 URL 地址。如果仓库的第一部分与你的用户名不完全匹配，它将无法正常工作，所以务必正确设置。

让我们开始吧！要更新此仓库的名称，点击此页面上的 `Settings` 选项卡。这将带你到仓库的设置页面。

![repo-settings-image](https://user-images.githubusercontent.com/18093541/63130482-99e6ad80-bf88-11e9-99a1-d3cf1660b47e.png)

在 **Repository Name** 标题下，键入：`username.github.io`，其中 username 是你在 GitHub 上的用户名。然后点击 **Rename**，就完成了。完成后，点击你的仓库名称或浏览器的返回按钮返回到此页面。

<img width="1039" alt="rename_screenshot" src="https://user-images.githubusercontent.com/18093541/63129466-956cc580-bf85-11e9-92d8-b028dd483fa5.png">

一旦你点击 **Rename**，你的网站将自动发布到：https://your-username.github.io/。HTML 文件 - 名为 `index.html` - 将被渲染为主页，你将在下一步中对此文件进行更改。

恭喜！你刚刚启动了你的第一个 GitHub Pages 网站。它现在已经上线，可以与全世界分享了。

## 进行你的第一个编辑

当你对项目中的任何文件进行更改时，你正在进行一次 **提交**。无论是更正拼写错误、更新文件名，还是编辑你的代码，你都可以将其添加到 GitHub 作为一次提交。你的提交代表着项目的整个历史 - 它们都保存在项目的仓库中。

对于每个提交，你都有机会写一条 **提交消息**，这是对你对文件进行的更改的简短而有意义的评论。因此，无论何时返回到提交，你都能确切地知道发生了什么变化。

## 实践：通过编写 HTML 代码定制你的第一个 GitHub 网站

想要编辑刚刚发布的网站吗？让我们通过在你的 `index.html` 文件中介绍你自己来练习提交。不用担心第一次就做对 - 你随时可以在以后完善你的介绍。

让我们从这个模板开始：

```
<p>Hello World! I’m [username]. This is my website!</p>
```

要添加你的介绍，复制我们的模板，并点击 `index.html` 文件右上角的编辑铅笔图标。

<img width="997" alt="edit-this-file" src="https://user-images.githubusercontent.com/18093541/63131820-0794d880-bf8d-11e9-8b3d-c096355e9389.png">

删除这个占位符行：

```
<p>Welcome to your first GitHub Pages website!</p>
```

然后，将模板粘贴到第 15 行并填写空白。

<img width="1032" alt="edit-githuboctocat-index" src="https://user-images.githubusercontent.com/18093541/63132339-c3a2d300-bf8e-11e9-8222-59c2702f6c42.png">

完成后，滚动到编辑页面底部的 `Commit changes` 部分。添加一条简短的消息解释你的更改，比如 "Add my introduction"，然后点击 `Commit changes`。

<img width="1030" alt="add-my-username" src="https://user-images.githubusercontent.com/18093541/63131801-efbd5480-bf8c-11e9-9806-89273f027d16.png)

一旦你点击 `Commit changes`，你的更改将自动发布到你的 GitHub Pages 网站。刷新页面以查看你的新更改在实际中的效果。

:tada: 你刚刚进行了你的第一个提交！ :tada:

## 额外加分: 不断构建！

通过 [创建你自己的个性化 Octocat 表情](https://myoctocat.com/build-your-octocat/) 或 [从我们的徽标库中选择不同的 Octocat gif](https://octodex.github.com/)，更改你的 GitHub Pages 网站上的占位符 Octocat gif。将该图像添加到 `index.html` 文件的第 12 行，替换 `<img src=` 链接。

想要在你的 GitHub Pages 网站上添加更多代码和有趣的样式吗？[按照这些说明](https://github.com/github/personal-website) 构建一个完整的静态网站。
