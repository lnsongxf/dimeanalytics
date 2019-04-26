# Software

This section lists step-by-step installation instructions for various software DIME Analytics recommends. Please let us know if any part of the instructions is not clear or does not work for you and we will improve the instructions, or if you would like to see any other software included.

## Dropbox

DIME members are allowed to utilize [Dropbox](https://www.dropbox.com/h) on personal and World Bank computers. Contact DIME Analytics to request an installation on a Bank machine, or start using your personal machine right away.

## Videoconferencing

The World Bank provides a WebEx subscription to all staff. You can access your account at the [corporate WebEx portal](http://worldbankgroup.webex.com) using your logon token. You can also use the desktop and mobile apps on Bank or personal machines without additional restriction. This is a more reliable way to have video conferences than, for example, Google Hangouts or Skype. The people you invite do not need an account, there is localized dial-in and dial-out capacity in many countries, and by inviting World Bank conference rooms (see the WebEx portal) the videoconference (VC) equipment in the room connects automatically once the meeting time starts.

## Remote Access to Bank Virtual Machines

You are able to access a virtual World Bank desktop from any personal computer using [Citrix Workspace](https://www.citrix.com/downloads/workspace-app/). This is close to, but not exactly the same, as you logging in to your World Bank desktop. The difference is that you will not have access to any software installed on your desktop in a local drive (for example Stata) and you will not have access to files saved locally (for example in the Documents folder). The virtual desktop is similar if you log in to a new World Bank computer for the first time. You will not have your local files, but you will have the network access, the one drive access, the intranet access etc. that you have from any World Bank desktop.

To log in to your Virtual Desktop follow the following steps:

1. [Download the Citrix software](https://www.citrix.com/downloads/workspace-app/) for the device you are using (PC, Mac etc.)
1. After the download is complete, open the software and follow instructions. When you are asked to enter email or server address enter: _myconnect.wbg.org_
1. Then you will be asked to enter your UPI (on the format _wb123456_), the windows password for your World Bank computer, and the passcode you are using for your token.
    1. If you are using an email token you will get one more window asking you to enter the code sent to your email.
1. After you are logged in you will get to menu where you can select which software you are accessing. You can also click Desktop to get a virtual version of a World Bank computer.

If you have never logged in on a World Bank computer and therefore do not have a Windows password yet, you should call IT support on 32121 from any World Bank phone, or +1-202-473-2121 from any phone.

This can also be set up by ITS to provide a secure and powerful server interface for your team to store and analyze data using Virtual Desktop Infrastructure (VDI).

## Stata & R

DIME has a [Stata MP](https://www.stata.com) license for use on Bank and personal laptops and Bank servers. [R and RStudio](https://www.rstudio.com) are free, and we additionally have a powerful RStudio Server and Shiny installation we can provide access to. Contact DIME Analytics for details.

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

#### Password Managers

Using a password manager is the most commonly recommended best practice for normal internet users (see examples [here](https://www.howtogeek.com/141500/why-you-should-use-a-password-manager-and-how-to-get-started/), [here](https://www.theverge.com/2017/7/24/15921282/best-password-manager-1password-lastpass-dashlane-how-to) or [here](https://www.pcmag.com/article/325635/get-organized-why-arent-you-using-a-password-manager-yet)) and should be used by everyone. They can generate and store strong passwords for your accounts, when you will need to use various logon names for personal and official business.

[LastPass](http://lastpass.com) is a popular and free password manager. It is most important that you are using any password manager, but the World Bank provides a free subscription to the premium features in LastPass for you. Visit the [LastPass Premium Partner Page](https://lastpass.com/partnerpremium/theworldbankgroup) to set up access.

#### Two-Factor Authentication (2FA)

If you combine two-factor authentication with a password managers then your life on the web is as secure as it could possibly be. The main drawback of most two-factor authentication methods is that it only works if you have your cell phone with you and it is charged. 2FA is required for most Bank-provided services via a logon token that is emailed to you whenever you attempt to access a secure service.

However, you should also protect your personal accounts, since they may contain sensitive personal or financial information. [Authy](https://authy.com/) is one exampe of a free software that enables two-factor authentication on your personal accounts. Setup is via [Authy for Apple iOS](https://itunes.apple.com/us/app/authy/id494168017) and [Authy for Android](https://play.google.com/store/apps/details?id=com.authy.authy).

#### Shared Drive (DropBox etc.) encryption
[VeraCrypt](http://veracrypt.fr) is a free encryption software that creates and manages "virtual thumb drives" that are inaccessible without a password. It can be used on World Bank machines to store and transfer sensitive data. Contact DIME Analytics for training.

## Atom Text and Code Editor

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
* [latex](https://atom.io/packages/latex): Compile LaTeX documents with Atom. (Atom can therefore replace TeXStudio also.)
* [hydrogen](https://atom.io/packages/hydrogen): See Stata results directly in your code. This is an advanced feature and we are happy to help you set this up.
* [teletype](https://atom.io/packages/teletype): Work on the same code file at the same time with any number of other people. This is _new_ software and can be a bit buggy but it can get you out of a pinch and is really cool.

## Our GitHub Repositories

### ietoolkit

[ietoolkit](https://worldbank.github.io/ietoolkit/) provides a set of commands that address different aspects of data management and data analysis in relation to [Impact Evaluations](http://blogs.worldbank.org/impactevaluations/ie-analytics-introducing-ietoolkit). The list of commands will be extended continuously, and suggestions for new commands are greatly appreciated. Some of the commands are related to standardized best practices developed at DIME (The World Bank’s unit for Impact Evaluations). For these commands, the corresponding help files provide justifications for the standardized best practices applied. See the [DIME Wiki entry](https://dimewiki.worldbank.org/wiki/ietoolkit) for more details.

### iefieldkit

[iefieldkit](https://www.github.com/worldbank/iefieldkit/) provides a set of commands that enable a reproducible primary data collection and cleaning workflow. The package is developed to facilitate a workflow including (1) data collection (in particular using opendatakit.org, more specifically surveycto.com); (2) basic data cleaning, such as labeling and recoding; (3) reconciling survey rounds; (4) preparing codebooks to document data sets. iefieldkit was developed to standardize and simplify best practices for high-quality primary data collection across the World Bank's Development Research Group Impact Evaluations team (DIME). The commands can also be used independently, and are developed to be applicable to many other contexts as well. See the [DIME Wiki entry](https://dimewiki.worldbank.org/wiki/Iefieldkit) for more details.

### World Bank Stata GitHub

The [World Bank Stata GitHub](https://worldbank.github.io/stata/) is an effort to debug, polish, improve, and disseminate useful reusable Stata code that is developed during the course of work. This repository is for such useful snippets – formalized as adofiles – which automate routine data management, statistical analysis, and graphing tasks such as data import and cleaning, production of summary statistics tables, and categorical bar charts with confidence intervals.

### Stata IE Visual Library

The [Stata IE Visual Library](https://worldbank.github.io/Stata-IE-Visual-Library/) is a repository maintained by DIME and containing example graphs on how to explore data sets and display results of Impact Evaluations using Stata.

### LaTeX Templates Library

The [LaTeX Templates Library](https://github.com/worldbank/DIME-LaTeX-Templates) contains resources that will help you make your research more reproducible. This will save you a substantial amount of time, significantly reduce the risk for human errors when exporting results to your papers, and make your research more transparent. We have prepared exercises that will make it easy for you to start using these resources.
