## IAS2018
A web site presenting topics related to IT and Society, done by S4 ICT students of EEB2 in school year 2017-2018.

#### To show the site in a browser:
https://eeb2.github.io/IAS2018

## Requirements:
- Every team creates a topic-specific folder to manage the files related to the topic.
- Create an `index.html` file in your folder. This is the main page of your topic.
- Every team creates a CSS file to change the look of the topic pages. Name it `styles_X.css` where X is replaced by your topic name (or its shorthand expression). Save the CSS file in the `styles` folder and add links to your pages to make it work.
- Present your topic in a simple and understandable way. Divide it into logical parts and make the site structure accordingly.
- Write your own text. Don't copy-and-paste text without a good reason - and in that case mark the source immediately. *Note: if you don't understand a word or an expression, don't use it! Write the idea in other words or leave it out.*
- Linking: you must be able to easily navigate between the pages in your topic folder. Preserve the link to the home of homes, too.
- Sources: make a separate HTML page to list the sources (give the links, too).
- Copyright: make sure you are allowed to use the images and other materials and follow the given source marking recommendations.

## Help for citing and sources:
- https://wiki.creativecommons.org/wiki/Best_practices_for_attribution (CC-licenced material).
- http://www.plagiarism.org/article/how-do-i-cite-sources

## Help for using ATOM, GIT and GITHUB:
- Create an account on Github.
- Find a repository to clone or create a new one.
- Download and install Atom editor from https://atom.io/.
- Download Git (Portable) to your computer (for instance Desktop but Mercury in not good here!)
- Copy the repository address from GitHub
- Start GitGuiPortable and Clone Existing Repository: for `Source Location` paste the GitHub repository address and `Target Directory` choose a folder on your computer (Hint: Onedrive folder / Mercury are now good places). *Note: add a slash "/" and type a new folder name. Seems to require that.*
- Click Clone and wait until all is done.
- Go to Repository -> Git Bash and paste the following text to set origin for Atom (didn't want to pull otherwise) and hit Enter:

`$ git branch --set-upstream-to=origin/master master`

- Then quit the GitGUI, you don't need it anymore.
- Open Folder in Atom and choose the folder containing the cloned repository. And there you are! The work flow goes like this:
#### 1) Pull (to get newest online version) 2) Edit 2) Stage and Commit 3) Push (asks for your GitHub username & password)

- http://rogerdudler.github.io/git-guide (Command line version of GIT)
