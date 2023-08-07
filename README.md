# 机器学习笔记

本项目为周志华《机器学习》的学习笔记，记录自己在机器学习上摸索的过程。

## 笔记查看

### PDF 阅读
本项目使用 Latex 编写，已编译 PDF 可直接下载查看。

### Latex 编译

本文给出 Linux 下使用 Latex 自行编译的过程：

操作系统：
```shell
Ubuntu 22.04.3 LTS x86_64 
```

tex 版本：

```shell
TeX 3.141592653 (TeX Live 2022/dev/Debian)
kpathsea version 6.3.4/dev
Copyright 2021 D.E. Knuth.
```

如需自行编译，请先行安装 `texlive`：

```shell
sudo apt install texlive-full
```

然后克隆本项目：

```shell
git clone https://github.com/3000ye/Machine-Learning.git
```

进入对应章节目录使用命令编译，如：

```shell
cd 1-绪论
xelatex 1-绪论.tex
```

需要注意的是，本文中文字体使用 Linux 中 tex 的默认字体，如需自定义中文字体请在此处自行更改字体：

```tex
\usepackage[UTF8]{ctex}
\usepackage{fontspec} % 设置字体
%\setCJKmainfont{SimSun}[AutoFakeBold=true, BoldFont={SimHei}, ItalicFont={KaiTi}] % 正文字体
%\setCJKsansfont[AutoFakeBold=3]{KaiTi} % 无衬线字体
%\setCJKmonofont[AutoFakeBold=3]{SimHei} % 等宽字体
\setmainfont{Times New Roman} % 设置主字体为新罗马体
```

## 习题解答

对应章节习题代码见另一个仓库。