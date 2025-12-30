<!--
 * @Author: 孙翊铭 && eamonsuen02@gmail.com
 * @Date: 2025-12-29 15:14:08
 * @LastEditors: 孙翊铭 && eamonsuen02@gmail.com
 * @LastEditTime: 2025-12-30 19:06:51
 * @FilePath: /Chinese-ERJ/README.md
 * @Description: 通用学术工作论文 LaTeX 模版
 * 
-->

# 通用学术工作论文 LaTeX 模版 (General Academic Working Paper Template)

> **Note:** 本项目 Fork 自 [EthanDeng/Chinese-ERJ](https://github.com/EthanDeng/Chinese-ERJ)，并在其基础上进行了通用化修改，旨在提供一个优雅、规范的中文经济学/管理学工作论文（Working Paper）排版方案。

## 简介 (Introduction)

原模版是为《经济研究》期刊投稿设计的专用模版。考虑到日常科研写作、课程论文以及工作论文（Working Paper）的需求，我对原模版进行了以下调整，使其更适合**通用学术写作场景**：

* **去期刊化**：移除了《经济研究》特定的期刊页眉、页脚标识，改为通用的“工作论文”样式。
* **页眉优化**：
    * 奇数页右侧显示年份与类型（如：`2025 年工作论文`）。
    * 偶数页左侧显示论文类型的自定义 Header（默认为“工作论文”）。
* **个人定制**：预设了常用的宏包配置，优化了中英文摘要页的布局。

本模版非常适合用于：
* 博士/硕士研究生课程论文 (Term Papers)
* 学术工作论文 (Working Papers)
* 研讨会展示文档 (Seminar Papers)

## 快速开始 (Quick Start)

### 1. 环境要求
推荐使用 **TeX Live 2020** 及以上版本。本项目依赖 `ctex` 宏包处理中文，以及 `biblatex` 处理参考文献。

### 2. 获取模版
点击本仓库右上角的 **"Use this template"** 按钮，直接基于本模版创建一个新的 GitHub 仓库开始写作。

或者克隆到本地：
```bash
git clone [https://github.com/你的用户名/仓库名.git](https://github.com/你的用户名/仓库名.git)
```

### 3. 编译方式

编译方式可以选择 `PDFLaTeX` 或者 `XeLaTeX`，注意一定要在编译过程中运行 biber：

1. xelatex -> biber -> xelatex -> xelatex
2. pdflatex -> biber -> pdflatex -> pdflatex

## 特别说明

由于本模板使用了 biblatex 定制《经济研究》的参考文献格式（chinese-erj），用户可以采用安装或者不安装的方式获取 biblatex-gb7714-2015 宏包。