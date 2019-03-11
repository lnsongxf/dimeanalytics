# Git and GitHub

If you want to be invited as a collaborator on a World Bank hosted repository or attend our _GitHub for Beginners_ training then you need the following two things in the list below. If you want to know what either of these two things are, then please read the rest of this page.

1. You need a GitHub.com account. If you do not already have one, create a free account [here](https://github.com/join). After you have done so, send your username to the team with the repository you want to be invited to as a collaborator, or send it to the person organizing the beginners training you intend to attend.
2. You need to install a Git Client on your computer. There are many clients to choose from and almost all of them are free. Which one you choose does not matter from a technical perspective, but in the beginner training we will show how to do things using the client [GitHub Desktop](https://desktop.github.com) which is free to use. If you already now know that you intend to use Git extensively, please read the section on Git Clients below.

If you are a World Bank employee and either want to access the features in the World Bank's paid enterprise account (we recommend you to do so), or if you want to create your own repository within the World Bank's account, see the _World Bank GitHub Group_ below.

## What is Git and what is needed to use Git?
Git is a tool that solves almost any code collaboration challenge you can think of. It is such a successful tool that all the code in all the software you are using to browse the internet and read this text right not is developed in Git. Recently tools have been developed that makes it easier to use Git also for researchers like us that collaborate on code, but do not have time to learn the technical tools that computer scientists use.

So while Git can be used in many ways, a research project usually depends on Git, a cloud host for Git (GitHub.com) and a Git Client. This is not more complicated than that your organization's email depends on emails, a cloud host for your emails (i.e. the webmail) and a desktop program that lets you write emails. See this comparison in the image below. You will eventually use Git/GitHub for more things than this, but for a beginner this is a good model to explain the difference between Git, GitHub and Git Clients. Each item is explained in more detail below.

![Screenshot](img/git_github_gitclient.png)

## Git

DIME projects are encouraged to use Git, a free [version control software](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004668), for writing data analysis code. They allow simultaneous editing and execution of code files and comparisons of histories and alternate versions. This enables maintaining and merging simultaneous ongoing workstreams without conflicts, unlike software like Dropbox.

## Git Clients

There are many desktop Git clients, but [GitHub Desktop](https://desktop.github.com) and [GitKraken](https://www.gitkraken.com) are supported on World Bank computers. GitHub Desktop is simple and therefore used in our training for absolute beginners, but we recommend anyone who intend to work a lot in Git to start using a more advanced git client like Git Kraken. Different people in the same project can use different clients, so a PI that only use Git occasionally can use GitHub Desktop, at the same time an RA use GitKraken. DIME Analytics offers regular Git trainings as well as on-demand onboardings for teams and PIs and can help you get this software up and running.

## GitHub

[GitHub](https://github.com/) is a web service that hosts a remote master copy of files you manage using Git. GitHub is just one of many places you can use to host your code, but The World Bank has a team subscription to this which you can join (see below) and that way get access to paid features. One GitHub alternative World Bank staff can use to create and manage your own remote Git repositories is [Microsoft Azure DevOps](http://devops.azure.com). You can create your repository there without any approvals using your World Bank email to login, although some features, like external collaboration, does not exist there.

### World Bank GitHub Group

DIME team members can join the [World Bank GitHub group](https://github.com/worldbank/) to have access to premium features. Here's how to sign up:

**1. Create a GitHub account**

- If you do not already have a GitHub account, open one at [this link](https://github.com/join). We recommend you DON'T use your World Bank e-mail, as you may lose access to it, and you CAN use a personal account you already have to become a member of this group.

**2. Join the World Bank GitHub group**

- Complete the World Bank GitHub.com Pilot MOU below, and email it to the World Bank GitHub team at [github@worldbank.org](mailto:github@worldbank.org) with the subject line "Request to Join World Bank GitHub Group - [YOUR NAME]". They will add you to the group and notify you.

```
World Bank Group Staff GitHub.com Pilot MOU:

I am aware that I am requesting access to the World Bank Group's GitHub.com group and any associated public and private repositories within that group.
I am aware that GitHub.com is an open source platform and that potentially any data uploaded could become available to the public.
I am aware that private repositories should be for working drafts of non-sensitive information only that are not yet ready for public viewing.
I agree not to post any confidential or sensitive information on any public or private GitHub.com repository.
I agree not to make public any repository without first consulting github@worldbank.org, and following any procedures then suggested.
I agree that I will comply with all relevant copyright laws and will not post copyrighted material to which I do not have release to do so.
I agree to maintain backups of any data I upload into a repository locally, and that these are updated at least once a month while the project is still active.
I agree that upon my departure of World Bank Group employment that I will remove any associated worldbank.org email addresses associated with my account, and notify github@worldbank.org of my departure.
I agree that I will keep my password secure; I will not share the user account with others and will not delegate administrative capabilities to non-World Bank Group staff.
I certify that I have read all the above and agree to the World Bank Group’s rules for accessing its GitHub.com repositories.

Name:

Github account name:
```

**3. Creating repositories**

- To create a repository in the World Bank GitHub group, send the following email to your manager and to [github@worldbank.org](mailto:github@worldbank.org) with the subject line "Approval Required: Create GitHub Repository [NAME]".

```
Hi [MANAGER], can you please approve the following request for GitHub repository creation:

Repository Name:

Repository Description/Purpose:

Team Name:

Team Maintainer:

I am aware that my employee named above as "Team Maintainer" is requesting creation of a code repository in the World Bank Group's Github.com site, for the purpose described above. This site allows for the publishing and public consumption of reproducible research and code. I agree that I have read the rules applicable to such access and agree to assist in upholding them to the best of my ability.

Manager's Name:
```

- The manager should reply to the email with a confirmation of approval and the GitHub team will then notify you when the repository is open.

- Repositories are private by default. If your repository will contain research code that is not ready to be shared with the world (e.g. data cleaning, exploratory analysis), you'll probably want to keep it that way.

- If the content of the repository can be public, it's occasionally easier to create it using your personal account. However, if you are creating a repo to share commands, or templates, or apps created as part of your project, or the replication folder for a paper, you may want it to be linked to the World Bank group so people can find it without having to look for your username.
