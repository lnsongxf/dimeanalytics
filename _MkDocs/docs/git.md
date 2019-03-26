# Git and GitHub

If you want to be invited as a collaborator on a World Bank hosted repository or attend our _GitHub for Beginners_ training then you need the following two things in the list below. If you want to know what either of these two things are, then please read the rest of this page.

1. You need a GitHub.com account. If you do not already have one, create a free account [here](https://github.com/join). After you have done so, send your username to the team with the repository you want to be invited to as a collaborator, or send it to the person organizing the beginners training you intend to attend.
2. You need to install a Git Client on your computer. There are many clients to choose from and almost all of them are free. Which one you choose does not matter from a technical perspective, but in the beginner training we will show how to do things using the client [GitHub Desktop](https://desktop.github.com) which is free to use. If you already now know that you intend to use Git extensively, please read the section on Git Clients below.

If you are a World Bank employee and either want to access the features in the World Bank's paid enterprise account (we recommend you to do so), or if you want to create your own repository within the World Bank's account, see the [World Bank GitHub Group](#wbg-github) section below.

If you are helping to organize a Git training with DIME Analytics, see [this checklist](#checklist-for-intro-to-git-and-github-training).

## What is Git and what is needed to use Git?
Git is a tool that solves almost any code collaboration challenge you can think of. It is such a successful tool that all the code in all the software you are using to browse the internet and read this text right not is developed in Git. Recently tools have been developed that makes it easier to use Git also for researchers like us that collaborate on code, but do not have time to learn the technical tools that computer scientists use.

So while Git can be used in many ways, a research project usually depends on Git, a cloud host for Git (GitHub.com) and a Git Client. This is not more complicated than that your organization's email depends on emails, a cloud host for your emails (i.e. the webmail) and a desktop program that lets you write emails. See this comparison in the image below. You will eventually use Git/GitHub for more things than this, but for a beginner this is a good model to explain the difference between Git, GitHub and Git Clients. Each item is explained in more detail below.

![git_github_gitclient](img/git_github_gitclient.png)

## Git

DIME projects are encouraged to use Git, a free [version control software](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004668), for writing and collaborating on data analysis code. Git allows simultaneous editing and execution of code files and very detailed comparisons of histories and alternate versions. This enables maintaining and merging simultaneous ongoing workstreams without conflicts, unlike software like Dropbox.

You do not need to understand how Git works to start using it. Our trainings are designed to introduce you gradually to the features you need to understand. If you are a beginner you only need to know how Git and GitHub are different things.

## GitHub

[GitHub](https://github.com/) is one out of many web services that can host the master copy of files you manage using Git. GitHub is the largest of those services, which is good if you want people to see your code and maybe even contribute to it. But you can also decide to keep your code private and only show it to people you decide to invite to your project.

The World Bank has a team subscription to this which you can join ([see below](#world-bank-github-group)) and that way get access to paid features. One GitHub alternative World Bank staff can use to create and manage your own remote Git repositories is [Microsoft Azure DevOps](http://devops.azure.com). You can create your repository there without any approvals using your World Bank email to login, although some features, like external collaboration, does not exist there.

## Git Clients

There are many desktop Git clients you can use to interact with the master copy of your Git files hosted on the web, but [GitHub Desktop](https://desktop.github.com) and [GitKraken](https://www.gitkraken.com) are two clients supported on World Bank computers. GitHub Desktop is simple and therefore used in our training for absolute beginners, but we recommend anyone who intend to work a lot in Git to start using a more advanced Git client like GitKraken. Different people in the same project can use different clients, so a PI that only use Git occasionally can use GitHub Desktop, at the same time an RA use GitKraken. DIME Analytics offers regular Git trainings as well as on-demand onboardings for teams and PIs and can help you get this software up and running.

### World Bank GitHub Group

DIME team members can join the [World Bank GitHub group](https://github.com/worldbank/) to have access to premium features. Here's how to sign up:

**1. Create a GitHub account**

- If you do not already have a GitHub account, open one at [this link](https://github.com/join). While you can use any email address, we **recommend using a personal email when you sign up** so that you do not lose access to your GitHub account in case you were to change job. There is no need to create a second account if you already signed up using a work email as you can add multiple secondary email addresses to your account, and later change which address is your primary email address. But we are recommending using a personal email when signing up in the first place, as we have had people lose access to their GitHub account after changing employer when using a work email as primary email.

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

### Checklist for Intro to Git and GitHub training:


* When planning the training:
    * **Organizer:** If people are attending remotely: Set up WebEx
    * **Organizer:** If people are attending in person: Make sure that the room is a VC room with a screen
    * **Organizer:** If people are attending both remotely and in person, do both of the above!
    * **Organizer:** Send out the instructions at the top of this page for what the participants needs before the training. Copy the facilitator on the email if that makes sense.
* A day or two before the training:
    * **Organizer:** Make sure that all participants has a GitHub account and a Git Client (GitHub Desktop if it is a beginner training). Send all the GitHub account names to the facilitator
    * **Organizer:** Make sure that all participants are aware that this is an interactive training where it only make sense if everyone brings their own computer doe the training.
    * **Facilitator:** Set up a training repo
    * **Facilitator:** Invite all participants to the training repo
* Day of training:
    * **Facilitator:** Check how many people accepted the invitation. If almost all accepted, then follow up at beginning of training, otherwise follow up by email as too much time will be spent doing this at the training.
    * **Facilitator:** Make sure that you do not have the test repo, or another repo with the same name, already cloned to your computer
