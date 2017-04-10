# Re:Coded Final Project Review Checklist

**Name of project developer**: Ahmed Alflahy

**Link to project's GitHub repository**: 
https://github.com/Ahmedalflahy/Ahmedalflahy.github.io
## Function
### AJAX Requests
- [No] All AJAX requests work properly.
- [Yes ] Large images, videos, and other media — anything that would significantly slow down the user's browsing experience — are loaded via AJAX requests.

### JavaScript Style
- [ Yes] Each page has its own JavaScript file that contains JavaScript written specifically for that page.
- [ yes] All functions have exactly **ONE** responsibility. No functions do more than one thing, like make an AJAX request *and* add the returned data to the DOM.
  + **List any functions that have more than a single responsibility**: 

## Form
### Pages
#### Homepage
- [ Yes] Project has a homepage.
- [yes] Homepage loads well-styled content even when JavaScript is disabled.
- [ yes but it should have some changes because it looks not professional ] Homepage contains links to all other pages.
- [Yes but there are some problem with the footer and there is no links for contact inside the homepage also the image should have some CSS style] Homepage makes the website's purpose clear (who owns the site / what we can expect to find within).

#### About
- [Yes] Project has an About page.
- [ No] Contains one paragraph about the student's life before Re:Coded.
- [ No] Contains one paragraph about why the student joined Re:Coded.
- [ No he didn't finish yet.] Contains one paragraph about what the student wants to do after Re:Coded, both short- and long-term.

#### Projects
- [yes ] Project has a Projects page.
- [  NO ther is to option in navbar one for current, one for favourit projects it should have one page!] Projects page contains two navigational buttons or tabs, `Current` and `Favorite`.
- [Yes ] Clicking the `Current` button makes an AJAX request to the GitHub API and displays information about the student's 5 most recent GitHub repositories.
- [ yes ] Clicking the `Favorite` button makes an AJAX request and displays a list of GitHub repositories (that the student created or contributed to) that the student is especially proud of.

#### Skills
- [ Yes ] Project has a Skills page.
- [NO ] Skills page displays information about all of the student's programming skills.
- [NO he didn't finish yet. ] Information about student's skills is stored in a JSON file in the project directory.
  + **Name of file**: 
- [ No ] Skills are added to the page by loading the JSON file via an AJAX request.

#### Student's Choice
- [ No ] Project contains at least one more page that displays data from an API *other than GitHub*.
  + **Which API**: 
- [ He didn't finish yet.] Page loads data via an AJAX call to the appropriate API.

## Style
### Overall
- [No he should have a good footer and navebar , add style for the image and the font size should have a better design, navbar should have just one option for projects not two in the contact page he should have one design and one size for the social logos.] Website looks professional.
  + **Why? Describe it**: 
- [Yes] Website does not feel cluttered.
- [ NO ] Spacing between similar elements is consistent across all pages. (For example, the amount of space between the navbar and the page's content is identical on every page.)
- [NO ] Sizing of similar elements is consistent across all pages. (For example, the navbar links on each page are identical.)
- [Yes ] All text is readable. For example, there isn't black text on top of a dark image or green text on a red background.
- [ Yes] Website has a uniform color scheme. Aside from images, the same base colors are used on every page of the site.
- [No It does not have a uniform style ] Website has a uniform style / layout. It should feel like one cohesive site and not just a random collection of pages thrown together.

### Code
- [ Bad ] JavaScript functions and variables have descriptive names.
  + Good: `var favoriteProjects = ...`
  + Bad: `function a (b, c, d) { ... }`
- [ Good] JavaScript functions and variables that are composed of English words are spelled correctly.
  + Good: `function sendRequestToGitHub (address, data, token) { ... }`
  + Bad: `function sndreqestGithub (adres, data, tokin) { ... }`
- [ Good] HTML elements and attributes (for example, IDs and classes) have descriptive names.
  + Good: `<project id="favoriteProject1" class="projects favoriteProjects">`
  + Bad: `<pj id="p1" class="ps fps">`
- [ Bad] HTML elements and attributes that are composed of English words are spelled correctly.
  + Good: `<project id="favoriteProject1" class="projects favoriteProjects">`
  + Bad: `<projet id="favritProjet1" class="projets favritProjets">`
  
### Content
- [Yes] There are no spelling or grammar errors in the site's textual content (including headings, navigational links, and other small elements).

### Pages
#### Student's Choice
- [He didn't finish yet] Student used one of the examples given in the [final project guidelines](https://github.com/gj/re-coded-js-final-project/blob/master/README.md).
  + **List example**: 
- [He didn't finish yet ] Student came up with their own, creative idea.
  + **List idea**: 
  
## Linters
- [ Ther is no issues inside the code. ] I ran the student's JavaScript code through [JSLint](http://jslint.com/) and told them about any JavaScript issues.
- [There is errors inside about.html, books.html,/certificat.html/contact.html and all html pages . ] I ran the student's HTML code through [the W3C's HTML validator](https://validator.w3.org/nu/) and told them about any HTML issues.
- [ No errors] I ran the student's CSS code through [CSS Lint](http://csslint.net/) and told them about any CSS issues.

**Name of reviewer**: Fatima Nasr.
