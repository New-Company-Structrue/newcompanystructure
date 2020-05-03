# newcompanystructure Readme

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/New-Company-Structrue/newcompanystructure)

newcompanystructure 样式

新型公司架构是一个基于区块链技术建立的平台系统，用于管理公司企业的日常运作。它的使用对象包括IT软件公司，地产行业，学校，工厂，酒店，购物超市等工作单位，几乎所有你能想到的工作场所，都可以使用该系统。本系统大胆创新，采用了独特的设计思路，该项目主要有以下一些内容：

1. 取代了人类组织架构中原始的金字塔模型，采用所有员工投票表决
方式决定公司日常事务。让公司的日常决定权掌握在所有员工手中，而不是某一少部分公司高层管理人员或者CEO手中。
2. 同时改变了现有公司的人事体制，每一个员工是否被录用，辞退都由全体员工投票表决。
3. 公司的所有现金流动，全部通过数字货币来实现。
4. 员工薪资，由平台设定好的算法来发放，无人能干预。
5. 求职者上传个人情况介绍视频，投递到求职者想要应聘的岗位上，公司内部所有员工观看每一位求职者的录像视频，从而投票表决录用哪一位成为公司员工。
6. 公司领导岗位，可以由任何一位员工参与公开竞选而获得，任何一个领导岗位，都必须是底层员工一人一票选举出来，不得由公司高层领导任命提拔。
7. 打破公司求职门槛，让全世界所有工作场所都变得开放。任何求职者不会因为学历，年龄，性别，宗教信仰，肤色，国籍，民族而受到影响。你可以去面试使用本系统的全世界任何一家公司，只要当该公司员工大多数投票赞同录用你，那么你就成为了该公司的员工。
8. 公司的运作情况全部在系统中公开，某个公司的人员情况，资产，负债，月收益，支出，公司投票表决记录，员工入职，离职数据，外界所有人都能直接看到，就好比你拥有某个比特币仓库地址，就可以查看该仓库里比特币数量一样。
9. 任何人可以通过数字货币购买该公司股份，成为该公司股东，享受股权分红，盈利。
10. 公司任何员工，都可以发起组建团队投票，在原有公司基础上，成立新的项目或者部门，能够从公司账户中获得资金支持。而这一切只需要公司全体投票超过一半即可。当你决定联合公司内部某些员工成立团队，就录制视频，说明你的项目构想和前景，使得你的项目能够说服公司至少一半以上的员工。
11. 员工可以投票调换工作岗位或者搭档，你可以和你关系好的人一起工作，从而不用和公司里你一些讨厌的人共处。





本仓库包含以下内容：

1. 一个标准的 README 文件应该是什么样子的[规范](spec.md)。
2. 一个用于维护 README 文件的语法提示工具的链接 ([正在进行中](https://github.com/RichardLitt/standard-readme/issues/5))。
3. 一个创建标准 README 的[生成器](https://github.com/RichardLitt/generator-standard-readme)。
4. 一个指向该规范的[徽章](#徽章)。
5. [标准 README 的实例](example-readmes/) - 比如你正在读的这个文件。
标准 Readme 是为了开源组件设计的。尽管它的[背景](#背景)是为了服务于 Node 和 npm 项目, 它同时也可以应用到其他编程语言和包管理器中去。

## 内容列表

- [背景](#背景)
- [安装](#安装)
- [使用说明](#使用说明)
	- [生成器](#生成器)
- [徽章](#徽章)
- [示例](#示例)
- [相关仓库](#相关仓库)
- [维护者](#维护者)
- [如何贡献](#如何贡献)
- [使用许可](#使用许可)

## 背景

`newcompanystructure` 项目的想法在我很早就有了，

> 如果你的文档是完整的，那么使用你代码的人就不用再去看代码了。这非常的重要。它使得你可以分离接口文档与具体实现。它意味着你可修改实现的代码而保持接口与文档不变。

> 请记住：是文档而非代码，定义了一个模块的功能。

—— [Ken Williams, Perl Hackers](http://mathforum.org/ken/perl_modules.html#document)

写 README 从某种程度上来说相当不易，一直维护下去更是难能可贵。如果可以减少这个过程，则可以让写代码与修改代码更容易，使得是否在说明中指明一处需改有无必要更加清楚，你可以花费更少的时间来考虑是否你最初的文档是否需要更新，你可以分配更多的时间来写代码而非维护文档。

同时，标准化在某些别的地方也有好处。有了标准化，用户就可以花费更少的时间来搜索他们需要的信息，他们同时可以做一个工具来从描述中搜集信息，自动跑示例代码，检查授权协议等等。

这个仓库的目标是：

1. 一个定义良好的**规范**。在仓库中的位置是 [spec.md](spec.md)。它是一个一直在持续优化的文档，欢迎您提 Issue 讨论其中的变化。
2. 一个**示例 README**。这个 Readme 完全遵从 Standard-readme，而且在 `example-readmes` 文件夹里有更多的示例。
3. 一个**语法提示器**用来提示在 Readme 中的语法错误。请参考 [tracking issue](https://github.com/RichardLitt/standard-readme/issues/5)。
4. 一个**生成器**用来快速搭建新的 README 的框架。请参考 [generator-standard-readme](https://github.com/RichardLitt/generator-standard-readme)。
5. 一个**标识准守规范的徽章**。请参考[徽章](#徽章)。

## 安装

这个项目使用 [node](http://nodejs.org) 和 [npm](https://npmjs.com)。请确保你本地安装了它们。

```sh
$ npm install --global standard-readme-spec
```

## 使用说明

这只是一个文档包，你可以打印出 [spec.md](spec.md) 到输出窗口。

```sh
$ standard-readme-spec
# Prints out the standard-readme spec
```

### 生成器

想要使用生成器的话，请看 [generator-standard-readme](https://github.com/RichardLitt/generator-standard-readme)。
有一个全局的可执行文件来运行包里的生成器，生成器的别名叫 `standard-readme`。

## 徽章
如果你的项目遵循 Standard-Readme 而且项目位于 Github 上，非常希望你能把这个徽章加入你的项目。它可以更多的人访问到这个项目，而且采纳 Stand-README。 加入徽章**并非强制的**。 

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

为了加入徽章到 Markdown 文本里面，可以使用以下代码：

```
[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)
```

## 示例

想了解我们建议的规范是如何被应用的，请参考 [example-readmes](example-readmes/)。

## 相关仓库

- [Art of Readme](https://github.com/noffle/art-of-readme) — 💌 写高质量 README 的艺术。
- [open-source-template](https://github.com/davidbgk/open-source-template/) — 一个鼓励参与开源的 README 模板。

## 维护者

[@RichardLitt](https://github.com/RichardLitt)。

## 如何贡献

非常欢迎你的加入！[提一个 Issue](https://github.com/RichardLitt/standard-readme/issues/new) 或者提交一个 Pull Request。


标准 Readme 遵循 [Contributor Covenant](http://contributor-covenant.org/version/1/3/0/) 行为规范。

### 贡献者

感谢以下参与项目的人：
<a href="graphs/contributors"><img src="https://opencollective.com/standard-readme/contributors.svg?width=890&button=false" /></a>


## 使用许可

[MIT](LICENSE) © Richard Littauer
