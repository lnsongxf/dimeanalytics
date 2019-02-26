# Code Review

## Pre-publication Code Review

When you submit a working paper for internal review, DIME Analytics will support review and release of the reproduction data and code via the [World Bank GitHub](https://github.com/worldbank). The goal is to ensure that working papers by DIME are fully reproducible. To complete this review, please submit the following to [dimeanalytics@worldbank.org](mailto:dimeanalytics@worldbank.org) alongside the submission of the working paper to the peer review process (currently organized by Dan Rogger):

1. The working paper submission, including tables and figures
    - Filenames for tables and figures **must** correspond to the paper
1. The directory that reproduces the results exactly, including:
    - The master do-file, which we will run
    - Dofiles required to produce result
    - All data required to produce the results
    - The TeX file that compiles the tables and figures (if applicable)

### Review Requirements

We are happy to review code for both reproducibility and any other requests the team may have, given reasonable notice and time constraints. The best method is to share a Dropbox folder or GitHub repository with all the necessary code and documentation included. In either case, the shared folder should be freshly created specifically for the review. There are some basic reproducibility requirements we enforce before beginning detailed code review, so it is usually good for the programming team to verify the following before submitting:

1. The “master” do-file is contained in the root directory of the shared folder and is the only do-file there;
1. There is one line in the master do-file that needs to be adjusted to set the location of the root directory; and
1. If this line and only this line is adjusted, then running the master do-file will correctly reproduce all materials from the project.

Once we verify that the code structure as a whole is fully reproducible in this sense, we will go on to review the code itself in the order suggested by the master file and provide any general suggestions, or address any specific questions about the code that the submitting team may have. Let us know if you might need any other information to prepare a package for review. Once received, DIME Analytics will edit *only* that top-level directory global in the master do-file and run it to reproduce the results. This portion of the code should be marked out as illustrated below:

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
The order of the outputted tables and figures should be obvious from the way they are named and organized. The Analytics team will return to you a list of reproducibility issues if any occur, as well as general (major and minor) suggestions for code improvements and places where existing programs can save time and effort for your future work, just as in a peer review.

## Public Release

Once this is complete, we can help to organize a public release repository on GitHub ([such as this example](https://github.com/worldbank/Water-When-It-Counts)). Let us know if you would like to do this and we are happy to help you set this up. Many journals now require data and code to be made publicly available, and the World Bank GitHub is a great place for this.

## Peer Code Review

It is also possible to request a review of a Research Assistant or Field Coordinator's code during the development of a project. This is recommended when a project milestone is reached, such as
- Handing over a project
- Finishing code for sampling and/or randomization
- Finishing the cleaning of a round of data collection
- Finalizing data analysis for a paper or report
- Preparing data for microdata catalog submission (more info on that in the [microdata catalog](https://dimewiki.worldbank.org/wiki/Microdata_Catalog) and [microdata submission checklist](https://dimewiki.worldbank.org/wiki/Microdata_Catalog) articles from the Wiki)

The project review is conducted by another RA or FC, and people submitting their codes are also required to review a peer's code. The goals of this exercise are to (1) make sure all work is reproducible, (2) reduce coding mistakes, (3) encourage adoption of best practices, (4) create an opportunity to learn new coding skills from other people's codes.

Project code review is currently being piloted but is expected to happen once a month. Participants will be asked to share their codes with the reviewer on a given date and will have a week to review their assigned project, following a guidelines provided by DIME Analytics.

**[Sign up a project for next round of code review](https://docs.google.com/forms/d/e/1FAIpQLScW1Holg5UjaA5F_kJ8Ga47eAV_zHE6JCGLot7DNOSraFMoFQ/viewform?usp=sf_link)**

**[Code review instructions](https://github.com/worldbank/DIMEwiki/wiki/How-does-it-work%3F)**
