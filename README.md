# PhoeniX-Thesis

PhoeniX 整个项目的论文，用于描述 PhoeniX 的设计和实现。

## 环境配置

本论文采用 Latex 编写，使用 Tex Live 编译，使用 VSCode 作为编辑器。

环境配置分为以下两步：

1. 安装 VSCode，并安装 Latex Workshop 插件

2. 根据[这个网站](https://github.com/James-Yu/LaTeX-Workshop/wiki/Install)的指引，安装 Tex Live

Tex Live 的相关工具需要被添加到系统环境变量中，若在命令行中输入`tex -v`后，能够正确显示版本号，则表示 Tex Live 已经安装成功。

## 常用 VSCode 命令

在 VSCode 中查看 Latex 的预览：
`Latex Workshop: View LaTex PDF file`

编译 Latex 论文：
`Latex Workshop: Build with recipe` -> `pdflatex->bibtex->pdflatex*2`

## 冯如杯格式

- 封面和题名页并不符合格式，需要使用 Word 生成 pdf 后手动替换这两页

- 关键词、图片和表格标题的加粗格式需要手动从生成的 pdf 中进行修改

- “目录”这两个字需要调整成华文中宋
