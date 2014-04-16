Hello-World
===========

$ mkdir ~/Hello-World
/*----# Creates a directory for your project called "Hello-World" in your user directory----*/

$ cd ~/Hello-World
/*----# Changes the current working directory to your newly created directory*/----

$ git init
/*----# Sets up the necessary Git files*/----
Initialized empty Git repository in /Users/you/Hello-World/.git/

$ touch README
/*----# Creates a file called "README" in your Hello-World directory*/----

/*----Think of a commit as a snapshot of your project — code, files, everything — at a particular point in time. After your first commit git will only save the files that have changed, thus saving space.*/

/*----Be warned: git will do it's best to compress your files, but large files and binaries can cause a repository to become bloated and unwieldy. Try to avoid committing things like compressed files (zips, rars, jars), compiled code (object files, libraries, executables), database backups, and media files (flv, psd, music, movies)----*/ 

$ git add README
/*----# Stages your README file, adding it to the list of files to be committed*/----

$ git commit -m 'first commit'
/*----# Commits your files, adding the message "first commit"*/----


/*----A remote is a repository stored on another computer, in this case on GitHub's server. It is standard practice (and also the default in some cases) to give the name origin to the remote that points to your main offsite repository (for example, your GitHub repository).----*/

Git supports multiple remotes. This is commonly used when forking a repository.

$ git remote add origin https://github.com/username/Hello-World.git
/*----# Creates a remote named "origin" pointing at your GitHub repository*/----

$ git push origin master
/*----# Sends your commits in the "master" branch to GitHub*/----

Tip: Notice that the path to your remote URL--Hello-World.git--matches the one that you created on GitHub. This is case sensitive, and important to keep the same.

/*----Congratulations! You have now created a repository on GitHub, created a README, committed it, and pushed it to GitHub. What do you want to do next? 1>Set Up Git (Completed) 2>Create A Repository (Completed above) 3>Fork A Repository 4>Be Social? ----*/

Fork a Repository - Contributing to a Project
=============================================

At some point you may find yourself wanting to contribute to someone else's project, or would like to use someone's project as the starting point for your own. This is known as "forking". For this tutorial, we'll be using the Spoon-Knife project, hosted on GitHub.com. https://help.github.com/articles/fork-a-repo

