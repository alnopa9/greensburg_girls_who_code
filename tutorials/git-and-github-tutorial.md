# Setting Up GitHub

The first thing we want to do for this course is to setup a GitHub account for each of you! It's easy and free!

Click the link to get started and follow the steps to create your own account. [GitHub](https://github.com/)

Why introduce you to GitHub?

Easy, it's the 'gold-standard' for today's programmers and, as of August 2019, there are over 100 million repositories with over 40 million people using it!
This will be a great tool to include in your coder toolbelt!

Another reason to use GitHub is because we will be using GitHub pages to host your sites.

## What is Git & GitHub
GitHub is an interface which works with Git, a version control software. 

How does this benefit us?

Well, imagine you are writing a poem and save it as code-poem.txt

    Roses are red,
    Violets are blue,
    Coding is cool,
    and so are you!

Now, let's say I make some changes to it:

    Roses are red,
    Violets are blue,
    What's cooler than coding,
    Girls coders, that's who!

With this new version, there are ways I can save it:

1. Save it as code-poem.txt 
    * This would overwrite my previous version, meaning I'd lose that work
1. Save it as code-poem-v2.txt
    * This doesn't seem as bad, because I woud still have both versions, but my directories would become *cluttered* with multiple files

This is where Git and GitHub comes in!

With Git, we would just save the second version as code-poem.txt but we wouldn't lose the previous version because Git keeps track of the changes for you!

### Downloading Git Shell

So, you've created your GitHub account, now we need to install [Git Shell](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

Git is available for download on all three of these platforms: Linux, Mac, and Windows. To download Git on your local machine follow the instructions available on the [git-scm.com site](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git). Since platform downloads differ we are not going to go through a step-by-step installation process.

Our suggested settings for a Windows installation are as follows:

 * When the download asks about Adjusting your PATH environment, we recommend selecting Use Git Bash only as it provides an unmodified PATH.
 * If the download asks about Configuring the line ending conversations, we recommend choosing the option to Checkout Windows-style, commit Unix-style line endings.
 * For ALL other settings choose the default selection.
 * Once installation is complete you will be asked if you want a desktop shortcut for Git Bash; make sure the box to create this shortcut is checked.

Installation on a Mac is much simpler. For a detailed installation guide, we suggest following [this tutorial](http://burnedpixel.com/blog/setting-up-git-and-github-on-your-mac/) for assistance while setting up Git on a Mac.

### Command Line

Now that you have Git on your computer you can access it through command line. On a Windows installation you will be using the **Git Bash command shell** and on a Mac installation you will be using **Terminal**.

The key thing to working with Git is always knowing where to find your files in the Finder (on Mac) / File Explorer (on Windows) and in the Terminal/Git Bash Shell. So you need to save directories in a place where you can easily see them. In your Finder/File Explorer, make yourself a GitHub directory that lives inside Documents (or on your desktop if that is a more logical place for you). Inside the GitHub directory you will clone each of your project repositories. In the Terminal/Git Bash Shell), you can navigate to your GitHub directory from the computer's root by typing: **cd Documents/GitHub/** if stored in documents or **cd Desktop/GitHub/** if stored on your desktop. **cd** means "change directories" and in the above command you are stepping down into Documents (or Desktop) and into the GitHub folder. Use **ls** to list out the contents of the directory you have stepped down into.

When you first use your command shell you will need to configure Git to recognize you local computer as a correspondent to your remote GitHub account. Use the following commands to configure your local Git installation (these command can be done in Terminal/Git Bash Shell without needing to specify a directory):

 * git config --global user.name "YOUR NAME"
 * git config --global user.email "YOUR EMAIL ADDRESS"

Be sure to use the same email address you used when signing up for your GitHub account. This will add your name and email to a file named .gitconfig in your home directory. To verify that you entered your information correctly use the command:

 * git config --list.

For more information on the **git config** command visit the [Pro Git guide on configuration](https://git-scm.com/docs/git-config). Note: in order to cache your username and password, you may need to follow further directions found on [help.github.com](https://help.github.com/en/articles/caching-your-github-password-in-git#platform-all). To test if your information has been cached try pushing to remote repositories that you have been added as a collaborator to on GitHub.

#### And There's More

There's so much that you can do with Git and GitHub! To learn more about repos and collaborators, there's a handy tutorial that my professor, Dr. Beshero-Bondar, wrote on her [Newtfire](https://newtfire.org/courses/dh/explainGitShell.html) server.
