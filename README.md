# writing-tools

Oddly specific and unique-to-my-setup tools for fiction writing. They probably won't be useful to you at all.

## fiction_template.org

An Emacs org-mode file that serves as a template for writing short fiction. Contains LaTeX headers and front-matter that will produce a correctly-formatted manuscript suitable for submission.

## manuscript.css

A css file meant for Marked.app, to format Markdown to look more like a standard "manuscript format" using a monospaced font.

## ms package

A copy of [Martin Schroeder's ms LaTeX package](https://ctan.org/pkg/ms?lang=en), plus some items from [M.C. DeMarco's sffms package](https://ctan.org/pkg/sffms?lang=en). I use a bunch of these LaTeX styles in my manuscripts and it's always annoying to find and install them if I need to rebuild my LaTeX environment... I'll keep a copy here so they're close at hand.

## titlesec package

A copy of [Javier Bezos López's titlesec package](https://ctan.org/pkg/titlesec?lang=en). I've started to use these .sty files in my manuscript as well, in order to hide org-mode section names. It's complicated.

## Installing LaTeX and packages

As a reminder for my future self:

- Install the [latest TeX Live from MacTeX](http://www.tug.org/mactex/).
- Feel free to install the Basic, smaller version
- Place ms/ and titlesec/ folders from this repo into /usr/local/texlive/2017basic/texmf-dist/tex/latex/
- Run sudo texhash so LaTeX can find the new .sty files and packages
- Cross your fingers
