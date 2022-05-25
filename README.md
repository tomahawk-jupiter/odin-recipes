# Odin Recipe Website Project

Odin Project Assignment: Basic website with just HTML and CSS. For learning the basics of Git and coding in my own local environment.

## Contents

- [Overview](#overview)
- [Assignment Instructions](#assignment-instructions)
- [Using Git and Github](#using-git-and-github)

- [Useful Things I Learnt](#useful-things-i-learnt)
- [Keyboard Shortcuts](#keyboard-shortcuts)
- [Include CSS in HTML](#inlude-css-in-the-html-file)

## Overview

In this project I will make an index page that has links to other pages that each contain a recipe.

The recipe pages will be in a seperate "pages" folder.

## Assignment Instructions

Each page will include in this order:

1. h1 heading of recipe name, each page should only have one h1 tag.
2. An image of the finished dish.
3. Appropriate size description heading, followed by a paragraph or two describing the recipe.
4. Ingredients heading followed by an unordered list of Ingredients.
5. Steps heading followed by an ordered list of steps for making recipe.

## Using Git and Github

I will use git to regulaly commit changes to the code and I will also push it to GitHub.

### Link Github repo

Create a new repo in github. Click the code button and copy the link to the repo.

Clone the repo:

    $ git clone <copied-link>

NOTE: dont't include the <> just the copied link. Paste in Cli with Ctrl + Shift + v.

### Git commands

Stage code changes:

    $ git add

Commit changes with a message:

    $ git commit -m "your commit message"

Commit changes and write commit message in editor (this can be a bit confusing):

    $ git commit

Push to github:

    $ git push origin main

See a list of previous commits:

    $ git log

Or show each on one line:

    $ git log --oneline

See the current status:

    $ git status

**Note**: don't include the '$' sign when typing commands, this is just to show that it is a command when written in documentation.

## Useful Things I Learnt

### Keyboard Shortcuts

View markdown in atom by pressing:

    Ctrl + Shift + M

Or in VSCode with:

    Ctrl + Shift + V

Close active window:

    Ctrl + W

fill out html boilerplate:

    type html then hit tab

In VSCode:

    Type ! then hit enter

Open file in browser (I think this is for windows cmd):

    $ start index.html

In Ubuntu and firefox:

    $ firefox index.html

## Inlude CSS in the HTML File

Add style sheet to html with head tags:

    <link rel="stylesheet" href="styles.css" />
