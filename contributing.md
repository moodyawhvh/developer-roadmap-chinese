> 🌐 本文档由 [nilbuild/developer-roadmap](https://github.com/nilbuild/developer-roadmap) 翻译,英文原版见原项目。

# ✨ 贡献指南 ✨

首先,感谢你考虑为本项目做出贡献。请查看以下说明:

- [新建路线图](#新建路线图)
- [现有路线图](#现有路线图)
- [添加项目](#添加项目)
- [添加内容](#添加内容)
  - [如何组织内容](#如何组织内容)
- [准则](#准则)
- [好的贡献与不太好的贡献](#好的贡献与不太好的贡献)
- [本地开发](#本地开发)

## 新建路线图

对于新建路线图,你可以:

- 在 [issue](https://github.com/nilbuild/developer-roadmap/issues) 中提交路线图,并附上[一份类似这样的文字版路线图](https://gist.github.com/nilbuild/98758d2c73799b3a6ce17385e4c548a5)。
- 使用[我们的路线图编辑器](https://draw.roadmap.sh/)自行创建交互式路线图,然后在 [issue](https://github.com/nilbuild/developer-roadmap/issues) 中提交该路线图的链接。

## 现有路线图

对于现有路线图,请根据贡献的性质参照以下说明:

- **修复错别字** — 直接在[路线图 markdown 文件](https://github.com/nilbuild/developer-roadmap/tree/master/roadmaps)中修改,并提交 [PR](https://github.com/nilbuild/developer-roadmap/pulls)。
- **添加/删除节点以及修改节点标题** — 请打开一个 [issue](https://github.com/nilbuild/developer-roadmap/issues) 说明你的建议。

**注意:** 我们的目标**并不是收录最多的条目**。我们的目标是列出当今最相关的条目或技能。

## 添加项目

如果你有一个认为应当加入路线图的项目点子,欢迎打开一个 issue,尽可能详细地描述该项目,并说明你认为它适合加入哪张路线图。

issue 的详细格式如下:

```md
## What is this project about?

(Add an introduction to the project.)

## Skills this Project Covers

(Comma separated list of skills, e.g. Programming Knowledge, Database, etc.)

## Requirements

( Detailed list of requirements, i.e. input, output, hints to help build this, etc.)
```

看看这个项目示例,就能了解[我们在寻找什么样的项目](https://roadmap.sh/projects/github-user-activity)。

## 添加内容

请在[相关路线图的 content 目录](https://github.com/nilbuild/developer-roadmap/tree/master/roadmaps)中找到对应位置。提交内容时请牢记以下准则:

- 内容必须使用英文。
- 每个主题最多 8 个链接。
- **不接受 GeeksforGeeks 链接** — 指向 geeksforgeeks.org 的链接不予接受。
- 内容请遵循下方的样式指南。

请注意,我们有意让主题弹窗中的内容保持简洁。你必须始终力求用**一个段落**左右的篇幅简明地解释该主题,并提供外部资源供用户进一步学习。

### 如何组织内容

向主题添加内容时,请遵循以下样式:

```md
# Topic Title

(Content)

Visit the following resources to learn more:

- [@type@Title/Description of Link](Link)
```

`@type@` 必须是以下之一,用于描述你所添加内容的类型:

- `@official@`
- `@opensource@`
- `@article@`
- `@course@`
- `@podcast@`
- `@video@`
- `@book@`

务必填写有效的类型,这有助于我们对内容进行分类,并在路线图上正确展示。链接按类型排列的顺序与上文相同。

## 准则

- <p><strong>请不要将本项目用于自我推广!</strong><br/>

  我们相信本项目是开发者社区的宝贵资产,其中包含大量有用的资源。恳请大家不要仅以自我推广为目的提交 Pull Request。我们欢迎真正带来价值的贡献,例如来自知名框架维护者的指南;即使这些内容是贡献者本人撰写的,我们也会考虑接受。感谢你的理解与配合!

- <p><strong>把现有的东西全部加进来并不是我们的目标!</strong><br/>

  路线图代表的是当今最有价值的技能组合。换句话说:如果你今天要进入其中任何一个领域,你会去学什么?当然,有些技术如今确实仍在使用,但请优先考虑当下需求最大的内容。举例来说,如今确实还有很多人在用 angular.js,但你不会想舍 React、Angular 或 Vue 而去学它。请用你的批判性思维过滤掉非必要的内容,并为该资源为何应当被收录给出中肯的理由。</p>

- <p><strong>不要添加你本人没有评估过的内容!</strong><br/>

  请用你的批判性思维过滤掉非必要的内容,并为该资源为何应当被收录给出中肯的理由。你读过这本书吗?你能为此写一篇短文吗?</p>

- <p><strong>内容添加请合并为一个 PR 提交</strong></p>

  如果你打算通过为路线图添加内容来做贡献,我建议你先克隆本仓库,把内容添加到[路线图的 content 目录](./roadmaps/)中,然后只创建一个 PR,这样更便于我审查和合并。

- <p><strong>撰写有意义的 commit message</strong><br/>

  有意义的 commit message 有助于加快审查进程,也能让其他贡献者无需逐条翻阅每个 commit,就能对仓库的提交历史有良好的整体了解。

  </p>
- <p><strong>在新建 issue/Pull Request 之前,先查看已有的 issue 和 Pull Request</strong></p>

## 好的贡献与不太好的贡献

<strong>好的贡献</strong>

- 新建路线图。
- 引人入胜且新颖的内容链接。
- 错别字和语法修复。
- 改进现有内容。
- 为尚无文案(或文案极少)的主题补充内容。

<strong>不太好的贡献</strong>

- 添加对内容可读性毫无帮助的空白。
- 对内容进行毫无价值的改写。
- 非英文内容。
- 不遵循我们的样式指南、没有描述、标题使用默认值的 PR。
- 指向你个人博客文章的链接。

## 本地开发

本仓库只存放路线图内容,没有需要运行的应用。克隆仓库,编辑 markdown,然后发起 PR 即可:

```bash
git clone git@github.com:nilbuild/developer-roadmap.git --depth 1
cd developer-roadmap
```

内容位于 `roadmaps/<roadmap-slug>/content/<topic-slug>@<node-id>.md`。请保持文件名不变,node id 正是把文件与路线图上的主题关联起来的关键。你的 PR 合并后,内容会自动同步到网站。

***

另请参阅 [License](./license)(许可证)文件。
