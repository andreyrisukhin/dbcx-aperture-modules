# dbcx-aperture-modules
A modular system for creating Portal 2 testing chambers in Lego

## Welcome!
This repository is a place for any person to create and modify the Modular Portal Testing Chamber project. See "Contributing to the project" for how to share your modifications with everyone.

## Getting Started

### Getting the files to build your own
It's as easy as downloading them! The fastest way might be to clone the entire repository, so you get everything. There are tutorials how to do this online. If you want a few specific files, it might be easiest to download those on their own. I'd ask that you also download the license from this repository. 

### Contributing to the project
Here's the process we'll use to incorporate community improvements to the project:
* Fork the repository to your GitHub account
* Make your own branch (name it something unique, maybe "yourusername-working")
* Switch to your new branch
* Make changes to files on your local branch. It's a good idea to write down all the changes you make to post them later in yuor pull request. This can be done through the website, no need to clone to your local machine for stud.io files.
* Add and commit your changes locally (committing involves writing a message of what you changed; it's a good idea to add and commit often, for small changes).
* Still on github, create a pull request from your forked repo unique branch to your forked repo's main branch. It's a good idea to add details here about broad changes, because the commit messages have fine-grained changes.
* Finally, create a pull request from your forked repo's main branch to the original repo's main branch. This is the place where to paste your changes to help us review your changes.

For Lego fans uploading stud.io files, working with the website for Github should be enough (just tested this). If you'd like the more involved process, this is a video walkthrough to contributing to an open-source project: https://www.youtube.com/watch?v=c6b6B9oN4Vg 

## Code of Conduct
Be cool, and don't be uncool. Let's make this a good experience for everyone involved, we're here to design and discuss the ultimate Lego version of modular aperture from Portal and Portal 2. 

## Organization
Files representing the most atomic elements are most useful. They allow easier comparisons between versions of an element. If proposing a new design, or modifying an element design, please submit a file containing only the element designed. Feel free to also submit example test chambers where the element is incorporated.

A "current" version of each element will live in a current folder, while previous replaced versions will be stored in an archive folder containing versions of previous elements. A subfolder will contain current example tests. When a piece of an example test is replaced, that test will be relegated to the archive folder. This preserves the invariant that "everything in the current folder is current".

A tutorial folder will exist to share information about topics such as rendering.

