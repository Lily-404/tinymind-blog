---
title: GoSearch：一个提升搜索效率的Go语言CLI工具
date: 2024-10-14T14:09:48.162Z
---

# GoSearch：一个提升搜索效率的Go语言CLI工具

在日常工作和学习中，我们经常需要在不同的搜索引擎之间切换以获取最准确的信息。然而，每次打开浏览器、输入网址、再进行搜索，这个过程既繁琐又耗时。为了解决这个问题，我开发了一个名为GoSearch的Go语言CLI工具，它允许用户在终端中快速切换和使用不同的搜索引擎，极大地提高了搜索效率。

## 项目简介

GoSearch 是一个基于Go语言开发的命令行工具，旨在为用户提供快速、便捷的搜索引擎切换和搜索体验。通过GoSearch，用户可以在不离开终端的情况下，轻松切换不同的搜索引擎进行搜索，大大提高工作效率。

## 特点亮点

### 1. 多搜索引擎支持

GoSearch支持多种主流搜索引擎，包括Google、Bing、Baidu、GitHub、ChatGPT、Perplexity、Jike、Bilibili、YouTube等。无论你需要查找技术文档、观看视频教程，还是进行学术研究，GoSearch都能满足你的需求。

### 2. 快速切换

用户可以在命令行中直接指定搜索引擎，无需打开浏览器即可进行搜索。例如，如果你想在Baidu上搜索“Go语言入门教程”，只需输入以下命令：

```bash
gosearch baidu "Go语言入门教程"
```

GoSearch会自动打开默认浏览器，并在Baidu上显示搜索结果。

### 3. 自定义设置

用户可以设置默认搜索引擎，方便日常使用。通过简单的命令即可更改默认搜索引擎，提升用户体验。例如，将默认搜索引擎设置为Google：

```bash
gosearch -s google
```

### 4. 跨平台

GoSearch支持Linux、Windows和macOS操作系统，确保在不同平台上的用户都能享受到便捷的搜索体验。

### 5. 易于安装和使用

通过简单的命令即可安装和使用GoSearch，用户无需复杂的配置即可快速上手。安装步骤如下：

1. 确保已安装Go语言环境。
2. 使用以下命令下载并安装GoSearch：

```bash
go get https://github.com/Lily-404/search
```

## 使用示例

以下是一些使用GoSearch的示例：

```bash
# 使用默认搜索引擎进行搜索
gosearch "如何学习Go语言"

# 指定搜索引擎进行搜索
gosearch baidu "Go语言入门教程"

# 设置默认搜索引擎
gosearch -s google
```

## 项目成果

GoSearch项目不仅提升了我的Go语言编程能力，还让我学习了如何开发跨平台的命令行工具。通过将项目发布到GitHub并进行宣传，我积累了丰富的项目开发经验，并提升了自己的技术影响力。

## 结语

GoSearch是一个简单而强大的工具，它让搜索变得更加高效和便捷。无论你是开发者、学生还是研究人员，GoSearch都能帮助你更快地获取所需信息。如果你对GoSearch感兴趣，欢迎访问[GitHub项目页面](https://https://github.com/Lily-404/search)了解更多信息，并参与到项目的开发和改进中来。
