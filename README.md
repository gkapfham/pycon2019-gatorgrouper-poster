# pycon2019-gatorgrouper-poster

![Sample of the PyCon 2019 Poster](gatorgrouper-poster-pycon2019.png)

This repository contains the LaTeX source code and additional resources for a
poster that [Gregory M. Kapfhammer](https://www.gregorykapfhammer.com/), with
the support of students in the Department of Computer Science at Allegheny
College, gave at the PyCon 2019 conference. The poster uses the
[rafaelbailo/betterposter-latex-template](https://github.com/rafaelbailo/betterposter-latex-template).
You are welcome to use this source code as inspiration for your own technical
poster. If you find this example useful, could I trouble you to star this
repository and then acknowledge it in your own presentation slides?

You can type the following command if you want to clone this repository:

```shell
git clone https://github.com/gkapfham/pycon2019-gatorgrouper-poster.git
```

Then, if you want to compile the presentation to a PDF, you should type the
following commands.

```shell
cd pycon2019-gatorgrouper-poster
pdflatex icsme2016-mccurdyc.tex
pdflatex icsme2016-mccurdyc.tex
```

If this does not work well because you notice that some of the icons are
rendering at a font size that is too small, then please try the following
commands instead.

```shell
cd icsme2016-presentation
xelatex icsme2016-mccurdyc.tex
xelatex icsme2016-mccurdyc.tex
```

Please note that this has been tested on an Arch Linux 4.7.6 workstation running
a recent version of LaTeX (pdfTeX 3.14159265-2.6-1.40.17 TeX Live 2016/Arch
Linux) that was installed using the [pacman package
manager](https://wiki.archlinux.org/index.php/pacman). It is worth noting that
you can also compile the paper using other LaTeX development tools, such as
`latexmk` (but note that to ensure certain icons are not sized correctly you may
need to configure `latexmk` to use `xelatex`). You may find that the placement
of certain `pgftikz` diagrams requires manual adjustment depending on your LaTeX
development environment and other settings. If you are unable to compile the
presentation with your development tools and your execution environment, then
please open a new issue and I will attempt to resolve your concerns.
