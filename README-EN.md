# NCHU_Bachelor_Thesis_Template

This project is an unofficial LaTeX template for **undergraduate** thesis of Nanchang Hangkong University.

This template is modified from [the Wuhan University Thesis Template](https://github.com/mtobeiyf/whu-thesis) and [the Beijing Institute of Technology Thesis Template](https://github.com/BITNP/BIThesis) with sincere thanks!

## Sample Display

![](https://i.loli.net/2021/01/31/ErnqwjiL3cWGMu8.png)

Please refer to [PDF sample document](main.pdf).

## Project Structure

```
.
├── README-EN.md
├── README.md
├── LICENSE
├── STXIHEI.TTF
├── chapters
│   ├── 0_abstract.tex
│   ├── 1_chapter1.tex
│   ├── 2_chapter2.tex
│   ├── 3_chapter3.tex
│   └── 4_chapter4.tex
├── images
│   ├── header.png
│   └── nchu_logo.png
├── main.pdf
├── main.tex
└── misc
    ├── 0_cover.tex
    ├── 1_originality.pdf
    ├── 1_originality.tex
    ├── 2_toc.tex
    ├── 3_conclusion.tex
    ├── 4_reference.tex
    ├── 5_appendix.tex
    ├── 6_acknowledgements.tex
    └── ref.bib
```

## Download

Download ZIP or `git clone`

## Usage

There are two methods to edit and compile LaTeX template:

* Overleaf
* Local

> It is recommended to use Overleaf online compliation.

### Overleaf

**Strongly Recommended**

Overleaf is a very convenient web-based online LaTeX editor. If you are an Overleaf premium user, you can sync with Github and even get some premium features.

![](https://i.loli.net/2021/01/31/OMbfg7Pza3xdGlR.png)

1. In this project interface, click `Download ZIP`
2. `New Project -> Upload Project`, upload the .zip file downloaded in step 1
3. Click the Menu button in the upper left corner, set the compiler type to XeLaTeX, and then click Recompiler to view the compiled page

### Local

Local compilation requires the installation of Tex softwares, such as TeX Live, MacTex and MikTeX. These softwares all come with basic LaTeX compilation tools.

**Note**: The system needs to install SimSun and SimHei fonts and Time New Roman English fonts, and please do not use CTeX.

#### Windows

You can install TeX Live or MikTeX in the system.

#### Mac

You can install MacTeX or MikTeX or TeXShop in the system.

#### Linux

You can install TeX Live or MikTeX in the system.

#### Configure VSCode LaTeX Workshop

1. Search and install LaTeX Workshop in the plugin on the left side of VSCode.

2. Download or clone this template and open the project folder with VSCode.

3. Click to open the `main.tex` file, click the `√` in the lower left corner, and select the first item `Build LaTeX Project`.

4. Select the first item `Recipe: latexmk (xelatex)`.

    In the TeX Live environment, use xelatexmk to compile the project.

5. If you are using MikTeX, you will be prompted to install the macro package midway. Wait util `√` is displayed again in the lower left corner, and then click to select the second item `View LaTeX PDF` to preview.

## Feedback

This template is still being maintained. If you encounter any problems using this template, you can [email me](hurleyhuang@hotmail.com), or leave a message in [Issues](https://github.com/NCHUSC/NCHU_Bachelor_Thesis_Template/issues), or access into my [personal homepage](https://withh.life).

## Follow-up Plan

* Support proposal report, lab report, etc.
* Support postgraduate thesis template, etc.
* Welcome to `Pull Request`.

