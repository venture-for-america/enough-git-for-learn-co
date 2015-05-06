## Enough Git for Learn

Learn has a deep integration with Git and Github. We need to teach you just enough git to interact with Github like a real developer. It'll be easy, just watch the video below.


## Summary

### `GitHub Fork`

Forking is the process of making a personal copy of the Learn lab on GitHub. It's basically how you tell Learn that you have started working on a lab.

![What's a Fork](http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/git-workflow-1.png)

To fork, just click the <img src="https://dl.dropboxusercontent.com/s/1fy8e0132r4f0pv/2015-05-06%20at%2011.38%20AM.png" style="display: inline"> button on GitHub.

![Fork on GitHub](http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/ironboard-labs-step-1.jpg)

Then select your personal Github account as the location to fork to.

![Fork to Your Account](http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/ironboard-labs-step-1b.jpg)

### `git clone`

Cloning is the process of downloading a copy of the lab from your personal fork on Github to your computer.

![What's a Clone](http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/git-workflow-2.png)

To clone, make sure you've first clicked on the SSH link (it starts with `git@github.com:` and not `https://github.com`, then click the  copy button next to the Clone URL to copy it to your clipboard (you can also copy it by selecting the text and copying it to your clibpoard as you would normally).

![The Clone URL](http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/ironboard-labs-step-2.jpg)

Next, in your Command Line (or Shell, or Terminal), navigate to the parent directory where you would like to place this lab. A good place would be in your `Development` directory within your home directory `~`. You can change directory in your terminal by typing `cd ~/Development`.

To clone a lab, type `git clone <the clone URL you copied from Github>`

It would look something like this: `git clone git@github.com:aviflombaum/first-lab-000.git`

You should see `git@github.com`, your username, like `aviflombaum`, and the lab you want to work on, like `first-lab-000`.

Type your clone command in your terminal and hit enter and you should see git download the lab to your computer.

### `git status`

Once you have a git repository locally, git will keep track of every change you make to the code in that folder. You can ask git what the differences or changes you've made since the last commit by typing `git status` into your terminal.

It's really helpful to constantly get the status from git to see what changes you need to stage, add, commit, or push.

### `git add`

Adding changes with the `git add` command is a way to stage any changes and get them ready to become a permanent record in your git log via a commit. The workflow worth memorizing right now is to simply add all your changes via `git add .`.

### `git commit`

A commit is a permanemt moment in time in your git history. A commit creates a new version of your code. To commit, memorize this command. `git commit -am "Your commit message"`. You are using the `git commit` command with the flags `-am`, which tell git to commit all the changes and to include a commit message. You supply the commit message in `""` directly in the command, `"Your commit message".

### `git push`



### `GitHub Pull Request`

## Resources

[GIT Cheatsheet](http://www.git-tower.com/blog/content/posts/54-git-cheat-sheet/git-cheat-sheet-large01.png)

[GIT Best Practices](http://www.git-tower.com/blog/content/posts/54-git-cheat-sheet/git-cheat-sheet-large02.png)

[Understanding the GitHub Flow](https://guides.github.com/introduction/flow)

[Hello World GitHub](https://guides.github.com/activities/hello-world)

[Forking on GitHub](https://guides.github.com/activities/forking)

[Git - The Simple Guide](http://rogerdudler.github.io/git-guide/)

[Git Immersion](http://gitimmersion.com/)

[Try Git](http://try.github.com/)