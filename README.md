# Odin Recipe Website Project

### Overview
In this project I will make an index page that has links to other pages that each contain a recipe.

The recipe pages will be in a seperate "pages" folder.

### Git Workflow
I will use git to regulaly commit changes to the code and I will also push it to GitHub.

1. Add to staging area.
2. Commit with or without message.
3. Check status or log.
4. Push to GitHub.

#### Git Commands

    $git add
    $git commit
    $git commit -m "message"
    $git status
    $git log
    $git push origin main

Note - don't include the '$' sign when typing commands.

### What the Pages Need

Each page will include in this order:
1. h1 heading of recipe name, each page should only have one h1 tag.
2. An image of the finished dish.
3. Appropriate size description heading, followed by a paragraph or two describing the recipe.
4. Ingredients heading followed by an unordered list of Ingredients.
5. Steps heading followed by an ordered list of steps for making recipe.

### Useful Tips I Found Along the Way
View markdown in atom by pressing:

    Ctrl+Shift+M

Close active window:

    Ctrl + W

fill out html boilerplate:

    type html then hit tab

Open file in browser:

    $start index.html

### CSS

Add style sheet to html with head tags:

    <link rel="stylesheet" href="styles.css" />

### Misc. useful CSS

calibri is a nice basic font.

    font-family: calibri;

Remove styling from list elements:

    list-style: none;

### Box Model

Put a border around all elements for an excellent demonstration of the box model:

    * {
      border: solid red 2px
    }

Alternate box model (padding and border included with content width and height):

    box-sizing: border-box;

Apply Alt box model to whole page:

    html {
      box-sizing: border-box;
    }
    
    *, *::before, *::after {
      box-sizing: inherit;
    }

##### Change display

        display: block;
        display: inline;
        display: inline-flex;

##### Span tags

        <span></span>
can be used to wrap words for styling purposes.
