## Two ways to contribute
There are two ways to contribute to this website - an easy way and an advanced way. The only advantage of the advanced method is that you can see the final formatted HTML version of the website before you send us your edits. In the easy method you will only see the text in markdown format until we have deployed the update for you.

If you want to just add a sentence or fix a typo, then you will be perfectly fine using the easy method. If should also be fine if you add a new paragraph as well. However, if you are adding a table, a new page or something big like that, then you should consider using the advanced method so you can see the results.

#### Which files to edit
Regardless if you are using the easy or the advanced method, the files you need to edit are exactly the same.

In this repo you will find a folder called `/_MkDocs/` and inside that folder you find a folder called `/docs/` that contains all the markdown files -- the text that goes into the HTML version of the website.

In the `docs` folder you see one file for each page on the [DIME Analytics website](https://worldbank.github.io/dimeanalytics/). They are named in a way that you should be able to figure out which file includes the text for the page you want to edit or add to.

### The easy method of contributing
The easy method might not be that easy if you are not familiar with GitHub, as the page uses GitHub's functionality to keep track of contributions. If you know what _branches_ and _pull requests_ are, then this should be easy for you.

You can either edit the files on GitHub.com in the browser or download (clone) the repo to your computer and use a code editor. In both these methods you will need a GitHub account.

#### Editing in browser on GitHub.com

If you are editing the file on GitHub.com then just go to that file and make edits to the content. When you are saving (committing) your work, GitHub.com will either create a fork on your account or branch in this repo (depending if you are in the DIME Team at the World Bank's GitHub account).

When you are done editing, submit a pull request from the fork or branch that GitHub created to the `master` branch in this repository, and we will review and publish your edits.

#### Editing in code editor on your computer

Clone the repository and create a branch. If you are not in DIME Team at the World Bank's GitHub account then you will have to fork the repository first. Edit the files you want to edit. Commit and push to the cloud and then submit a pull request to the master branch in this repository and we will review your edits, and upload them.

### The advanced method of contributing

The main benefit of this method is that you can render the website on your local computer and look at the final result as you are making your edits. This is great if you are experimenting with some advanced formatting.

This website is built using the command line tool [`MkDocs`](https://www.mkdocs.org) using the theme [Material](https://squidfunk.github.io/mkdocs-material/). You need to install both the tool and the theme to be able to render the website locally. They are easy to install if you have [pip](https://pypi.org/project/pip/) installed on your computer. The [`MkDocs`](https://www.mkdocs.org) guide has a less technical guide about installing _pip_.

Once you have _pip_ installed you install `mcdocs` and `mkdocs-material` like this using your _command line_, _terminal_ window, _bash_ or any other console.

```
pip install mkdocs
pip install mkdocs-material
```

Next step is to clone this repository if you have not already done so. Go to the folder `/_MkDocs/docs/` folder to find the files you want to edit. Make your edits and save the files. If you want to see the result of your edits before sending them to us, then do the following:

Open an console window (_command line_, _terminal_, _bash_ etc.) and make sure that you are in the `/_MkDocs/` folder in the repository in the branch where you have saved your edits. If you are not in the right place, nothing will happen (unless you are in another folder with a `_mkDocs` website), so do not be afraid to test if you are not sure.

In that folder, run this in your console `mkdocs build`. This should create another folder `/_MkDocs/site/` with many sub-folders. In the `/site/` folder you should also find a file called `index.html`. Click that file and it should open as a webpage in your default browser.

If you click on any link you will not get to the next page immediately since you are browsing the files locally and that works slightly different. What will happen depends on your browser or if you are using a Mac or a PC. In Safari on a Mac, for example, you are taken to a folder in the `/site/` folder in finder where you will find another `index.html` file that you can click on to get to the page the link was pointing to.

In Google Chrome on a PC you will get to a page that looks like the image below. There you click on the `index.html` link and you will get to the link destination.
![image](https://user-images.githubusercontent.com/15911801/53442678-da9d3b00-39d7-11e9-9c37-fd7d45748aa3.png)

When you are done with your edits, submit a pull request with your edits to the master branch, and we will review your edits and then upload them.

## Uploading new edits to https://worldbank.github.io/dimeanalytics/

This section is only for admin users with access to the `master` and the `gh-pages` branches. Those branches are locked so that only WB account admins and @bbdaniels and @kbjarkefur can edit them. Everyone else should make their edits and submit a pull request to the master branch.

When new edits have been merged to the `master` branch then do the following:

1. Build the website using `mkdocs build` and make sure that the new edits has not broken anything on the website.
1. Then run `mkdocs deploy` from the `/_mkDocs/` folder and make sure that you do not get any errors. If not, then the new edits are published!
