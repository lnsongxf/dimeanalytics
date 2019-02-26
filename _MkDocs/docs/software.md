# Software

This section lists step-by-step installation instructions for various software DIME Analytics recommends. Please let us know if any part of the instructions is not clear or does not work for you and we will improve the instructions, or if you would like to see any other software included.

## Dropbox

DIME members are allowed to utilize [Dropbox](https://www.dropbox.com/h) on personal and World Bank computers. Contact DIME Analytics to request an installation on a Bank machine, or start using your personal machine right away.

## Stata & R

DIME has a [Stata MP](https://www.stata.com) license for use on Bank and personal laptops. [R and RStudio](https://www.rstudio.com) are free, and we additionally have a powerful RStudio Server and Shiny installation we can provide access to. Contact DIME Analytics for details.

## SurveyCTO

DIME Analytics administers the [World Bank's enterprise subscription with SurveyCTO](https://survey.wb.surveycto.com/). This installation is available to all Bank teams at a discount from the retail subscription and uses Bank single-sign-on when possible as well as allowing external email accounts. Please review the [World Bank SurveyCTO Documentation](https://showcase.dropbox.com/s/WBG-SurveyCTO-Documentation-HZN82ovmFR0hpnnsLYdns) and use eServices to request a server. To be added to the DIME Team for survey template sharing, please contact DIME Analytics.

## Git & GitHub

DIME projects are encouraged to use [Git](https://git-scm.com), a free [version control software](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004668), for writing data analysis code. They allow simultaneous editing and execution of code files and comparisons of hisotries and alternate versions. This enables maintaining and merging simultaneous ongoing workstreams without conflicts, unlike software like Dropbox. [Learn more here.](https://worldbank.github.io/dimeanalytics/git/)

## LaTeX

[LaTeX](https://www.latex-project.org) is a text-based typesetting language. It can support full version control with Git, simultaneous online editing, or collaboration over Git/GitHub. [Overleaf](http://overleaf.com) is an online collaborative LaTeX editor that works much like Google Docs and includes a very useable rich-text editor. [TeXStudio](https://www.texstudio.org) is a desktop-based suite that works well with Git and is available for self-installation. Both allow the use of [BibTeX](http://www.bibtex.org) for reference management, which [pandoc](http://pandoc.org) can translate into correctly cited Microsoft Word documents (and much more!) using the [Citation Styles library](https://github.com/citation-style-language/styles):

```
pandoc -s -o main.docx main.tex --bibliography sample.bib --csl=/.../styles/the-lancet.csl
```

## Security and Data Encryption

[LastPass](http://lastpass.com) is a free web app and software that manages your passwords. [Authy](https://itunes.apple.com/us/app/authy/id494168017?mt=8) is a software that enables two-factor authentication on your personal accounts. You should definitely use these both for all your personal and official data.

[VeraCrypt](http://veracrypt.fr) is a free encryption software that creates and manages "virtual thumb drives" that are inaccessible without a password. It can be used on World Bank machines to store and transfer sensitive data.

## Our GitHub Repositories

### ietoolkit

[ietoolkit](https://worldbank.github.io/ietoolkit/) provides a set of commands that address different aspects of data management and data analysis in relation to [Impact Evaluations](http://blogs.worldbank.org/impactevaluations/ie-analytics-introducing-ietoolkit). The list of commands will be extended continuously, and suggestions for new commands are greatly appreciated. Some of the commands are related to standardized best practices developed at DIME (The World Bank’s unit for Impact Evaluations). For these commands, the corresponding help files provide justifications for the standardized best practices applied.

### World Bank Stata GitHub

The [World Bank Stata GitHub](https://worldbank.github.io/stata/) is an effort to debug, polish, improve, and disseminate useful reusable Stata code that is developed during the course of work. This repository is for such useful snippets – formalized as adofiles – which automate routine data management, statistical analysis, and graphing tasks such as data import and cleaning, production of summary statistics tables, and categorical bar charts with confidence intervals.

### Stata IE Visual Library

The [Stata IE Visual Library](https://worldbank.github.io/Stata-IE-Visual-Library/) is a repository maintained by DIME and containing example graphs on how to explore data sets and display results of Impact Evaluations using Stata.

### LaTeX Templates Library

The [LaTeX Templates Library](https://github.com/worldbank/DIME-LaTeX-Templates) contains resources that will help you make your research more reproducible. This will save you a substantial amount of time, significantly reduce the risk for human errors when exporting results to your papers, and make your research more transparent. We have prepared exercises that will make it easy for you to start using these resources.

## Atom

[Atom](http://atom.io) is a powerful free text editor that has easy integrations with Git/GitHub and Stata, as well as other languages and softwares like LaTeX and Markdown. You can set it up on a personal computer with administration privileges. We are currently working on setup instructions for World Bank computers.

1. First install Atom from <https://atom.io/>. Choose any theme you like!
1. In Atom, go to _Settings_ and then _Install_ and install the following two packages **language-stata** and **stata-exec**.
1. In _Settings_ / _Packages_, open **stata-exec** and read the instructions carefully.
    * _For Mac users_: Selecting the correct Stata version should be the only step. Ask for help if you don't understand something.
    * _For Windows users_: It is a bit more complicated. You need to follow [these](https://github.com/kylebarron/stata-exec#installation) instructions. Ask for help if you don't understand something.
1. Now open a Stata .do file in Atom and run it using the keyboard shortcuts in the **stata-exec** settings. The default keyboard shortcuts are slightly different than in the Stata dofile editor: `shift-cmd-d` (on Macs) and `shift-ctrl-d` (on PC) runs the whole file, and `cmd-alt-d` (on Macs) and `ctrl-alt-d` (on PC) runs only the selected code block. Let us know if you want to change these!

_Useful Atom Packages:_

* [file-icons](https://atom.io/packages/file-icons): Adds icons to the project sidebar.
* [fonts](https://atom.io/packages/fonts): Supports beautiful programming fonts like [atom-firacode](https://atom.io/packages/firacode).
* [chary-tree-view](https://atom.io/packages/chary-tree-view): Stops Atom from trying to open .dta and .xlsx files.
* [indent-guide-improved](https://atom.io/packages/indent-guide-improved): Helps you understand the structure of your code and be a better coder.
* [minimap](https://atom.io/packages/minimap): Shows you a zoomed-out view of your code so you can navigate faster.
* [zebra-stripes](https://atom.io/packages/zebra-stripes): Makes alternating lines different colors in the editor (very good for coding).
* [language-latex](https://atom.io/packages/language-latex): Provides code highlighting for LaTeX.
* [latex](https://atom.io/packages/latex): Compile LaTeX documents with Atom. (Atom can replace TeXStudio also 😉)
* [hydrogen](https://atom.io/packages/hydrogen): See Stata results directly in your code. This is an advanced feature and we are happy to help you set this up.
* [teletype](https://atom.io/packages/teletype): Work on the same code file at the same time with any number of other people. This is _new_ software and can be a bit buggy but it can get you out of a pinch and is really cool.
