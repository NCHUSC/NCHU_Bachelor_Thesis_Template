 # 南昌航空大学本科毕业论文 LaTeX 模版

[English Version](README-EN.md)

本项目为非官方的南昌航空大学**本科生**毕业论文 LaTeX 模版。

本模版由武汉大学毕业论文 LaTeX 模版 [mtobeiyf/whu-thesis](https://github.com/mtobeiyf/whu-thesis) 和北京理工大学本科生毕业设计（论文）模版 [BITNP/BIThesis](https://github.com/BITNP/BIThesis) 修改而成，特此表示衷心的感谢！

## 样例展示

![](https://i.loli.net/2021/01/31/ErnqwjiL3cWGMu8.png)

正文样例可以参照[PDF样例文档](main.pdf)

## 项目结构

```
NCHU_Bachelor_Thesis_Template
├─ .gitignore
├─ chapters
│  ├─ 0_abstract.tex
│  ├─ 1_chapter1.tex
│  ├─ 2_chapter2.tex
│  ├─ 3_chapter3.tex
│  └─ 4_chapter4.tex
├─ images
│  ├─ header.png
│  └─ nchu_logo.png
├─ LICENSE
├─ main.pdf
├─ main.tex
├─ misc
│  ├─ 0_cover.tex
│  ├─ 1_originality.pdf
│  ├─ 1_originality.tex
│  ├─ 2_toc.tex
│  ├─ 3_conclusion.tex
│  ├─ 4_reference.tex
│  ├─ 5_acknowledgements.tex
│  ├─ 6_appendix.tex
│  └─ ref.bib
├─ README-EN.md
├─ README.md
├─ SimHei.ttf
├─ SimKai.ttf
└─ SimSun.ttc
```

## 下载方式

Download ZIP 或者`git clone`。

## 使用方法

有两种方式进行编辑和编译：

* Overleaf 在线编译
* 本地编译

> 推荐使用 Overleaf 在线编译的方式。

### Overleaf 在线编译
**强烈建议大家使用**  

Overleaf 是一个十分方便的网页版在线 LaTeX 编辑器。如果是 Overleaf 会员用户的话，甚至可以与 Github 同步。

![](https://i.loli.net/2021/01/31/OMbfg7Pza3xdGlR.png)

1. 在本项目界面，选择 Download ZIP
2. 在 Overleaf 页面的 New Project，Upload Project，上传第 1 步下载的 zip 文件
3. 点击左上角的 Menu 按钮，设置 Compiler 类型为 XeLaTeX，然后点击 Recompiler，即可查看编译好的页面

### 本地编译

本地编译需要安装 TeX 发行版软件，例如 TeX Live、MacTeX 和 MikTeX，这些发行版都自带了基本的 LaTeX 编译工具。

**注意**：系统需要安装有宋体（SimSun），楷体（SimKai）和黑体（SimHei）字体以及 Times New Roman 英文字体，**并请不要使用 CTeX**。

#### Windows

可以在系统中安装 TeX Live 或者 MikTeX。

#### Mac

可以在系统中安装 MacTeX 或者 MikTeX 或者是 TeXShop。

#### Linux

可以在系统中安装 TeX Live 或者 MikTeX。

#### 配置 VSCode + LaTeX Workshop

1. 在 VSCode 左侧的插件栏搜索 LaTeX Workshop 并安装

2. 下载或者克隆本模版，用 VSCode 打开项目文件夹

3. 点击打开`main.tex`文件，点击左下角的`√`的符号，选择第一项`Build LaTex Project`

4. 选择`Recipe: latexmk (xelatex)`

    即在 Tex Live 环境下，使用xekatexmk进行编译

5. 如果是使用 MikTeX，中途会提示安装宏包。等左下角再次显示`√`，再点击，选择第二项`View LaTeX PDF`，即可进行预览。

## 问题反馈

本模板仍在维护，如果在使用本模板遇到任何问题，可以[发邮件给我](hurleyhuang@hotmail.com)，或者在 [Issues](https://github.com/NCHUSC/NCHU_Bachelor_Thesis_Template/issues) 中留言，亦可前往我的[个人主页](https://hurleywong.com)。

## 后续计划

* 支持开题报告、实验报告模版等
* 支持研究生论文模版等
* 欢迎提交 Pull Request
