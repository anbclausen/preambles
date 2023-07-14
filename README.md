# Preambles for LaTeX
Welcome to my personal collection of preambles. I have built these preambles in my time at Aarhus University for handins, exams, and presentations. I hope they will be useful for you. Feel free to use, distribute and modify them!

## What can I do with your preambles?
Great question! See [Article Example](article-example.pdf) for an example of how to write an article/a document. This example also lists all features of all the preambles with examples. See also [Presentation Example](presentation-example.pdf) for an example of how to write a presentation.

## How do I use your preambles?
You need to add this repository as a git submodule with
```
cd root/of/your/git/project
git submodule add https://github.com/anbclausen/iris-cheatsheet.git
```
After this, you can just follow the examples. To make a minimal article compile
```
\input{preambles/article}

\title{Your Title}
\author{Author}
\date{\today}

\begin{document}
\maketitle
...
\end{document}
```
with `pdflatex`.

Alternatively, you can download this repo and place the `preambles/` folder next to your `.tex` files.

Good luck!