# Welcome to DIME Analytics!

This website is the GitHub home of DIME Analytics. It is meant to serve as a guide to the services DIME Analytics offers DIME team members. For questions not answered here, please contact [dimeanalytics@worldbank.org](mailto:dimeanalytics@worldbank.org). If you are a new hire, please visit the [Quick Start page](https://showcase.dropbox.com/s/DIME-New-Hire-Onboarding-Guide-LyXosHJuWwjZKKT74Or8K). If you are an external visitor, you may be looking for our [official World Bank page](http://www.worldbank.org/en/research/dime/brief/DIME-Analytics). All other materials and resources are located below.

DIME Analytics supports research workflows and best practices at DIME and creates public goods to increase the research quality for impact evaluation and development economics generally. In 2016, DIME staff supervised 15 baseline surveys and 22 follow-up surveys representing over $7.5 million in client executed funds. DIME Analytics supports DIME projects directly through training, code review and reproducibility support, and technology solutions.

We take advantage of the concentration and scale of research at DIME to develop and test solutions, first to ensure high quality of data collection and research quality across our portfolio, and, second, to make public training and tools available to the larger community of development researchers who might not have the same capabilities. The resulting products are offered to the development research community at large through software releases, structured trainings and the DIME Wiki, a comprehensive wiki with resources on all phases of impact evaluation.

Our team gathers, documents, standardizes and disseminates these produces and practices to (1) ensure that all DIME surveys follow established best practices in data analysis and research transparency and (2) keep tools, protocols, guidelines, and training materials publicly available and up-to-date in a rapidly changing field.

## DIME Analytics Services

### New Hire Testing and Onboarding

DIME Analytics has recently concluded the Spring 2018 Recruitment Drive. Until the next Recruitment Drive launches, we supports the ad-hoc administration of the DIME Technical Tests for Research Assistant and Field Coordinator candidates as needed. Please contact [dimeanalytics@worldbank.org](mailto:dimeanalytics@worldbank.org) for more details.

### World Bank SurveyCTO Enterprise Server

DIME Analytics administers the World Bank's enterprise subscription with SurveyCTO. This installation is available to all Bank teams at a discount from the retail subscription and uses Bank single-sign-on when possible as well as allowing external email accounts. Please review the [World Bank SutveyCTO Documentation](https://showcase.dropbox.com/s/WBG-SurveyCTO-Documentation-HZN82ovmFR0hpnnsLYdns) and use eServices to request a server. To be added to the DIME Team for survey template sharing, please contact DIME Analytics.

### World Bank GitHub

DIME team members can join the World Bank GitHub group, which allows the creation of private repositories. Here's how it's done:

#### 1. Create a GitHub account

- If you do not already have a GitHub account, open one at [this link](https://github.com/join?source=header-home). You don't need to use your World Bank e-mail and you can use an account you already have as a member of this group.

#### 2. Join the World Bank GitHub group

- Complete the GitHub pilot MOU below, and email it to the World Bank GitHub team (github@worldbank.org) with the subject line "Request to Join World Bank GitHub Group - [YOUR NAME]". They will add you to the group and notify you.

```
World Bank Group Staff Github.com Pilot MOU:

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

#### 3. Create your repositories

- To create a repository in the World Bank GitHub group, send the following email to your manager and to github@worldbank.org with the subject line "Approval Required: Create GitHub Repository [NAME]".

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

#### 4. Clone the GitHub repo to your computer

- Click `Clone or download` on your repo's main page, then `Open in Desktop` and `Allow`. It's best practice to have your GitHub folder on your local computer, not in Dropbox, and sync changes using GitHub Desktop. If you insist on having this folder on Dropbox, please get in touch with the Data Coordinators to discuss the details on how to do it.

- [This presentation](https://www.dropbox.com/s/mvf895eofw0ok3o/Git.pdf?raw=1) gives full details on how to sync a Git repo for the first time. 

### Pre-publication Code Review

When you submit a working paper for internal review, DIME Analytics will support review and release of the reproduction data and code via the [World Bank GitHub](https://github.com/worldbank). The goal is to ensure that working papers by DIME are fully reproducible. To complete this review, please submit the following to [DIME Analytics](mailto:dimeanalytics_internal_use_only@worldbank.org) alongside the submission of the working paper to the peer review process (currently organized by Dan Rogger):

1. The working paper submission, including tables and figures
1. The directory that reproduces the results exactly, including:
    - The master do-file
    - All dofiles required to produce results
    - The data required to produce the results
    - The TeX file that compiles the tables and figures (if applicable) 

## Review Requirements

DIME Analytics will edit *only* the top-level directory global in the master do-file and run it to reproduce the results. This portion of the code should be marked out as illustrated below:

```
   * ******************************************************************** *
   *
   *       PART 1:  PREPARING FOLDER PATH GLOBALS
   *
   *           -Set the global box to point to the project folder
   *            on each collaborators computer.
   *           -Set other locals that point to other folders of interest.
   *
   * ******************************************************************** *

   * Users
   * -----------

   *User Number:
   * You                     1    //Replace "You" with your name
   * Next User               2    //Assign a user number to each additional collaborator of this code

   *Set this value to the user currently using this file
   global user  1

   * Root folder globals
   * ---------------------

   if $user == 1 {
       global projectfolder "/Users/bbdaniels/GitHub/dime-msie-track2-solutions/"
   }
```
The order of the outputted tables and figures should be obvious from the way they are named and organized. The Analytics Team will return to you a list of reproducibility issues if any occur, as well as general (major and minor) suggestions for code improvements and places where existing programs can save time and effort for your future work, just as in a peer review.

#### Public Release

Once this is complete, if you desire we will organize a public release repository on GitHub ([such as this example](https://github.com/worldbank/Water-When-It-Counts)). This will contain all the files needed to reproduce the results, including a version of the datasets you provide, stripped to contain only the variables needed for analysis (using [exportCodebook](https://github.com/worldbank/stata/tree/master/src/exportCodebook)). *Please let us know if any other data may not be publicly released so we can remove the appropriate materials from the repository!* We will share a private repository with you once it is created, and make it public once the working paper is released.

### Peer Code Review

### Trainings

## Public Resources

### DIME Wiki

### Manage Successful Impact Evaluations

### 

## External Resources

### Stata

### Methods
