<p align="center">
  <a href="https://dshplugin.dev/">
    <img src="assets/dsh-plugin-mark.svg" width="96" height="96" alt="dshplugin.dev Logo" />
  </a>
</p>

# Awesome DSH Plugin

<p align="center"><strong>面向 DeepSeek Harness 用户的产品说明书与插件导航。</strong></p>

<p align="center">
  <a href="README.md">English</a> ·
  <strong>简体中文</strong> ·
  <a href="README.ja.md">日本語</a> ·
  <a href="README.es.md">Español</a>
</p>

先看用途和风险，再前往 [dshplugin.dev](https://dshplugin.dev/) 查看完整详情。点击上方 Logo 也可直接进入网站。

[![Website](https://img.shields.io/badge/浏览插件-dshplugin.dev-0B6E5F)](https://dshplugin.dev/)
[![Baseline](https://img.shields.io/badge/受控公开基线-87-2563EB)](https://dshplugin.dev/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## 这是什么

DeepSeek Harness（简称 DSH）采用“Everything is a Plugin”的扩展方式。社区插件可以补充开发工具、自动化、浏览器操作、界面设计、会话管理、模型接入、安全控制和存储能力。

这个仓库不讲源码、API 或插件开发。它帮助普通使用者回答四个问题：

1. 我需要哪一类插件？
2. 安装前应该检查什么？
3. 去哪里看插件的最新资料？
4. 出现兼容性或权限问题时怎么办？

仓库中的每个插件名称都跳转到 `dshplugin.dev` 的独立详情页。本仓库只链接 2026-08-17 核验的 87 个公开基线页面，不会把采集器发现的每个项目都变成公开推荐。详情页会汇总发布者、用途、安装命令、许可证、语言、仓库活跃度和原始来源，再由你决定是否前往发布者页面。

> [!IMPORTANT]
> `dshplugin.dev` 是独立社区目录，不是 DeepSeek 官方网站，也不代表 DeepSeek 或插件发布者的认可。公开仓库、Star 数和更新时间都不能证明插件安全、兼容或持续维护。

## 从这里开始

| 你的目标 | 推荐入口 |
| --- | --- |
| 直接搜索插件名称或用途 | [插件总目录](https://dshplugin.dev/) |
| 第一次安装 DSH 插件 | [安装与验证指南](https://dshplugin.dev/guides/install-deepseek-harness-plugins) |
| 看刚通过发布复核的项目 | [新发布插件](https://dshplugin.dev/collections/new-releases) |
| 找近期仍在更新的项目 | [最近更新](https://dshplugin.dev/collections/recently-updated) |
| 用 GitHub Star 作为初步参考 | [最多 Star](https://dshplugin.dev/collections/most-starred) |
| 按作者或团队查看作品 | [发布者目录](https://dshplugin.dev/publishers) |
| 了解收录与纠错规则 | [编辑政策](https://dshplugin.dev/editorial-policy) |
| 查看生态规模与分类趋势 | [生态报告](https://dshplugin.dev/reports/deepseek-harness-plugin-ecosystem) |

## 按需求选择

以下分类只覆盖 2026-08-17 核验的 87 个受控公开基线页面。候选、隔离和拒绝记录不会出现在本仓库，即使某个过渡期 URL 暂时仍可打开，也不在这里继续传递链接。

| 分类 | 适合你在什么时候使用 | 快照数量 | 完整导航 |
| --- | --- | ---: | --- |
| Developer Tools | 想增强代码、终端、文件、调试、API 或本地工作流 | 46 | [查看公开基线](catalog/developer-tools.md) |
| Automation | 想把重复任务、Agent 协作或跨工具流程自动化 | 10 | [查看公开基线](catalog/automation.md) |
| Browser | 需要网页操作、搜索、采集、测试或浏览器桥接 | 9 | [查看公开基线](catalog/browser.md) |
| UI & Design | 想改善界面、主题、可视化、设计或预览体验 | 6 | [查看公开基线](catalog/ui-design.md) |
| Models | 需要模型适配、路由、回退或推理服务接入 | 2 | [查看公开基线](catalog/models.md) |
| Sessions | 需要会话历史、记忆、上下文和对话工作流 | 9 | [查看公开基线](catalog/sessions.md) |
| Security | 关注权限、沙箱、策略、密钥或防护能力 | 5 | [查看公开基线](catalog/security.md) |
| Storage | 需要持久化、数据库、缓存或产物存储 | 0 | [查看基线状态](catalog/storage.md) |

## 如何理解收录状态

“发现项目”和“允许公开”是两个独立步骤。自动采集器可以产生项目线索，但不能把项目直接写入这个公开导航。

| 状态 | 对使用者意味着什么 |
| --- | --- |
| 公开基线 | 来自 Search Console 已索引历史基线，本仓库保留链接以维持稳定 URL；它不代表已完成新一轮人工质量复核，也不是安全认证。 |
| Candidate | 通过初步自动检查、等待人工复核；本仓库不提供链接。 |
| Quarantined | 证据不足，暂时无法确认是有实质功能的 DSH 插件；不进入公开目录。 |
| Rejected | Archived、不可访问、空仓库或触发其他硬门禁；被排除，后续采集不能自动复活。 |

生态报告中的发现量和审计总量可能高于本仓库数量。这是有意设计：优先保证内容质量和稳定索引，不再把每个被发现的仓库都做成公开页面。

也可以直接打开官网分类页：

- [Developer Tools](https://dshplugin.dev/categories/developer-tools)
- [Automation](https://dshplugin.dev/categories/automation)
- [Browser](https://dshplugin.dev/categories/browser)
- [UI & Design](https://dshplugin.dev/categories/ui-design)
- [Models](https://dshplugin.dev/categories/models)
- [Sessions](https://dshplugin.dev/categories/sessions)
- [Security](https://dshplugin.dev/categories/security)
- [Storage](https://dshplugin.dev/categories/storage)

## 一套稳妥的使用流程

### 1. 先把基础 Harness 跑通

首次使用时，先按官方快速启动方式运行 Web UI：

```sh
npx @deepseek-ai/dsh web
```

默认地址是 `http://127.0.0.1:3080`。在安装任何第三方插件之前确认基础功能正常，后续遇到问题时更容易定位原因。

### 2. 在官网详情页做初筛

打开插件详情页，至少检查：

- 它解决的问题是否与你的需求一致；
- 安装命令是否完整，并且来自发布者当前文档；
- 目标 profile、DSH 版本和系统环境是否匹配；
- 最近更新时间、Issue 状态和维护说明；
- 许可证是否满足你的个人或商业使用场景；
- 是否依赖外部服务、账号、密钥或付费 API；
- 是否展示截图、演示或可复现的真实结果。

### 3. 安装前检查权限

插件本质上是第三方代码。涉及下列权限时，应先阅读源码和发布者说明：

- 读写本地文件或执行终端命令；
- 控制浏览器、读取页面或使用登录态；
- 访问网络、上传内容或调用外部 API；
- 读取环境变量、凭据、会话和聊天记录；
- 修改模型路由、审批策略或安全设置。

如果详情页没有安装命令或权限说明，把它视为“可供了解”，不要根据仓库名猜测命令。

### 4. 一次只验证一个能力

1. 使用发布者给出的完整命令，不随意删除 profile、分支或版本信息。
2. 刷新或重启对应 profile，确认插件没有加载或审批错误。
3. 运行文档中最小、可逆的示例。
4. 只授予该功能确实需要的权限。
5. 记录仓库地址和安装版本，确保能复现或回退。

## 如何比较两个插件

不要只看 Star 数。建议按下面顺序比较：

| 维度 | 要问的问题 |
| --- | --- |
| 需求匹配 | 它是否准确解决你的问题，还是只在描述中提到 DSH？ |
| 安装清晰度 | 是否提供完整命令、目标 profile 和前置条件？ |
| 兼容性 | 是否标明支持的 DSH 版本、操作系统和已知限制？ |
| 权限范围 | 权限是否与功能相称，能否使用最小权限？ |
| 可验证证据 | 是否有截图、演示、示例输入输出或测试说明？ |
| 维护信号 | 最近是否更新，Issue 是否得到回应，是否说明破坏性变更？ |
| 许可证 | 能否满足个人、团队或商业场景？ |
| 可退出性 | 是否容易禁用、卸载或回退？ |

## 常见问题

### 插件安装后没有出现

重新核对 profile、包名、分支或标签，然后查看 Harness 界面和发布者 Issue 中是否有加载错误。不要连续叠加安装多个插件，否则会增加排查难度。

### 更新后突然不能用了

DeepSeek Harness 仍处在快速迭代阶段，官方明确提示可能发生兼容性破坏。对照 Harness 版本、插件最后更新时间和发布者的兼容说明，必要时回到已记录的可用版本。

### 插件要求很大的权限

先暂停。确认权限与核心功能直接相关，检查源码、权限理由和 Issue 记录。无法解释的文件、浏览器、网络或密钥访问不应直接授权。

### 网站收录是否等于推荐或安全认证

不是。收录表示目录发现并整理了公开来源信息，不等于安全审计、兼容认证、质量担保或官方推荐。

### 为什么本仓库数量和实时生态报告不同

本仓库只导航受控公开基线；官网报告还会包含发现、复核、发布与下线过程中的不同状态，因此总量会更大。本仓库不会为了追平发现量而给候选、隔离或拒绝页面增加链接。

## 数据范围与更新

- 本次导航快照：2026-08-17
- 受控公开基线：87 个插件页
- 基线中有条目的分类：7 个，Storage 暂无基线条目
- 数据来源：公开 GitHub 仓库、npm 元数据和发布者页面
- 实时状态：[生态报告](https://dshplugin.dev/reports/deepseek-harness-plugin-ecosystem)
- 收录方法：[编辑政策](https://dshplugin.dev/editorial-policy)

插件名称、简介、许可证和活跃度可能随发布者更新而变化。仓库内分类清单是受控导航快照，不是所有候选项目的镜像；插件详情页和发布者原始资料才是判断当前状态的依据。

## 提交、纠错与收录

如果你是插件作者：

1. 保持仓库公开，并写清用途、安装、兼容性、权限、许可证和示例。
2. 在 GitHub 仓库添加 `dsh-plugin` topic。
3. 等待下一次抓取和人工发布复核。
4. 阅读 [插件提交指南](https://dshplugin.dev/submit)。

如果详情错误或项目缺失，可通过 [联系页](https://dshplugin.dev/contact) 或本仓库 Issue 提交公开来源证据。贡献方式见 [CONTRIBUTING.md](CONTRIBUTING.md)。

## 独立声明

本仓库与 [dshplugin.dev](https://dshplugin.dev/) 均为独立社区项目，与 DeepSeek 无隶属关系，也未获得 DeepSeek 或任何被收录发布者的背书。DeepSeek、DeepSeek Harness、各插件名称、Logo 与商标归各自权利人所有。

## License

[MIT](LICENSE)
