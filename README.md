# superninja

Test repository following The Net Ninja on Youtube. This also includes some items other items that I found along the way to creating my first website 200 hours into [MIT xPRO Professional Certificate in Coding](https://executive-ed.xpro.mit.edu/professional-certificate-coding?utm_source=Google&utm_network=g&utm_medium=c&utm_term=full%20stack%20course&utm_location=9002000&utm_campaign_id=17460394007&utm_adset_id=138322132500&utm_ad_id=594796992655&gclid=Cj0KCQjwuO6WBhDLARIsAIdeyDI4f2ioANuLnoK5AlsUEcxxuJRtgjOcmWWvZCD5sXpfTX1oBWrsiEoaAnzmEALw_wcB) online course.

[Gitting Started with GitHub Pages](https://www.youtube.com/watch?v=QyFcl_Fba-k)

[Git & GitHub Tutorial for Beginners](https://www.youtube.com/playlist?list=PL4cUxeGkcC9goXbgTDQ0n_4TBzOO0ocPR)

# Commit changes to repo via Visual Studio Code Terminal

I wasted a lot of time trying to understand how to create and modify repositories by dragging documents from my computer and placing them in a repository. The github website is really busy from the eyes of a begginer. Learning how to use Visual Studio Code Terminal to make changes to repositories was a huge step for me.

You need to set up an [SSH key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) before you can use the ```git``` commands listed below.

Create a new repository at GitHub.com and copy the SSH key. Open terminal to the directory that contains your code.

```git clone replace this text with ssh key```

```git status``` check branch

```git add .``` full stop to add all changes

```git commit -m initialcommit``` "initialcommit" is the change control description

```git push origin main``` push changes to the "main" branch in your github repository.

```git checkout -b site``` creates a new branch called "site". Make a new branch, then goto github and use pull request to merge with main branch Project: Might not want to serve up the project using the main branch. We might want a web site to accompany the project, not host the project. [Add, remove switch branches](https://devconnected.com/how-to-switch-branch-on-git/)

# html
```<a href="/superninja/contact.html">superninja contacts</a>``` Anchor Tag <a>: Link to an html; file path starts with /insert repo name/insert file

# GitHub [Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

Use this link to format your README. You can create ```quote code like this``` or format lists or create links or add images. There are many things you can do to communicate clearly.

# Styles CSS

Grid: MIT xPro Week 8; Video 8-7 (6:08) Holy Grail
  
# Local Server
```npx http-server```
In Terminal, goto directory and create a local host for that directory.

# [Destructuring](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment)
