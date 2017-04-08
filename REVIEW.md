# Re:Coded Final Project Review Checklist

**Name of project developer**: Fatima Nasr

**Link to project's GitHub repository**: https://github.com/fatimaberazi/fatimaberazi.github.io

## Function
### AJAX Requests
- [she only did the project current repo and it worked] All AJAX requests work properly.
- [no inages loaded via AJAX requests it's just 2 images untill now ] Large images, videos, and other media — anything that would significantly slow down the user's browsing experience — are loaded via AJAX requests.

### JavaScript Style
- [she finished just project page and it has js file ] Each page has its own JavaScript file that contains JavaScript written specifically for that page.
- [ There is a function with 2 responsibility in peoject page] All functions have exactly **ONE** responsibility. No functions do more than one thing, like make an AJAX request *and* add the returned data to the DOM.
  + **List any functions that have more than a single responsibility**: function callRepos in project.js

## Form
### Pages
#### Homepage
- [ yes] Project has a homepage.
- [yes ] Homepage loads well-styled content even when JavaScript is disabled.
- [ yes] Homepage contains links to all other pages.
- [yes mostly ] Homepage makes the website's purpose clear (who owns the site / what we can expect to find within).

#### About
- [ yes but it's not filled yet] Project has an About page.
- [ ] Contains one paragraph about the student's life before Re:Coded.
- [ ] Contains one paragraph about why the student joined Re:Coded.
- [ ] Contains one paragraph about what the student wants to do after Re:Coded, both short- and long-term.

#### Projects
- [yes but the name was project not projects ] Project has a Projects page.
- [ yes] Projects page contains two navigational buttons or tabs, `Current` and `Favorite`.
- [yes ] Clicking the `Current` button makes an AJAX request to the GitHub API and displays information about the student's 5 most recent GitHub repositories.
- [ not throgh AJAX request] Clicking the `Favorite` button makes an AJAX request and displays a list of GitHub repositories (that the student created or contributed to) that the student is especially proud of.

#### Skills
- [yes but not done yet ] Project has a Skills page.
- [ no] Skills page displays information about all of the student's programming skills.
- [ no] Information about student's skills is stored in a JSON file in the project directory.
  + **Name of file**: not yet
-[not yet ] Skills are added to the page by loading the JSON file via an AJAX request.

#### Student's Choice
- [ no] Project contains at least one more page that displays data from an API *other than GitHub*.
  + **Which API**: not yet
- [no ] Page loads data via an AJAX call to the appropriate API.

## Style
### Overall
- [it's not finished I can't say my opinion  ] Website looks professional.
  + **Why? Describe it**: 
- [ ] Website does not feel cluttered.
- [ ] Spacing between similar elements is consistent across all pages. (For example, the amount of space between the navbar and the page's content is identical on every page.)
- [ ] Sizing of similar elements is consistent across all pages. (For example, the navbar links on each page are identical.)
- [ ] All text is readable. For example, there isn't black text on top of a dark image or green text on a red background.
- [ ] Website has a uniform color scheme. Aside from images, the same base colors are used on every page of the site.
- [ ] Website has a uniform style / layout. It should feel like one cohesive site and not just a random collection of pages thrown together.

### Code
- [Good ] JavaScript functions and variables have descriptive names.
  + Good: `var favoriteProjects = ...`
  + Bad: `function a (b, c, d) { ... }`
- [Good] JavaScript functions and variables that are composed of English words are spelled correctly.
  + Good: `function sendRequestToGitHub (address, data, token) { ... }`
  + Bad: `function sndreqestGithub (adres, data, tokin) { ... }`
- [ Good] HTML elements and attributes (for example, IDs and classes) have descriptive names.
  + Good: `<project id="favoriteProject1" class="projects favoriteProjects">`
  + Bad: `<pj id="p1" class="ps fps">`
- [Good ] HTML elements and attributes that are composed of English words are spelled correctly.
  + Good: `<project id="favoriteProject1" class="projects favoriteProjects">`
  + Bad: `<projet id="favritProjet1" class="projets favritProjets">`
  
### Content
- [Good ] There are no spelling or grammar errors in the site's textual content (including headings, navigational links, and other small elements).

### Pages
#### Student's Choice
- [not yet ] Student used one of the examples given in the [final project guidelines](https://github.com/gj/re-coded-js-final-project/blob/master/README.md).
  + **List example**: 
- [not yet ] Student came up with their own, creative idea.
  + **List idea**: 
  
## Linters
- [yes ] I ran the student's JavaScript code through [JSLint](http://jslint.com/) and told them about any JavaScript issues.
- [yes ] I ran the student's HTML code through [the W3C's HTML validator](https://validator.w3.org/nu/) and told them about any HTML issues.
- [ yes] I ran the student's CSS code through [CSS Lint](http://csslint.net/) and told them about any CSS issues.

**Name of reviewer**: Fatima Mohammad
