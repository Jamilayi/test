# Part 2 - Git and Github
So, you've set up your machine, you've read the readme and you're ready to go. Setting up can be complicated and frustrating, so good job getting here! The bad news is that you'll probably find the rest of this tutorial complicated and frustrating, but hey, at least you're used to the feeling now.

### Basics of Git
Git has some terminology associated with it that is important to understand. What's nice is that once you understand the terminology, you understand Git (you can tell yourself that at least).

Before moving on you should be understand the following terms: _branch_, _commit_, _commit message_, _merge_, _repo_, _remote_, _clone_, _push_ and _fork_. A good place to start is [here](http://www.git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging).

### Basics of Git part 2: The Inquisition
What do the terms _branch_, _commit_, _commit message_, _merge_, _repo_, _remote_, _clone_, _push_ and _fork_ mean?

6 out of 9 means you passed. If you read the readme before taking the test, give yourself a bonus point (note: bonus points are only good for the first time the test is taken).

### Choosing a branching model (except you don't get to choose)
A _branching model_ is basically a sensible way of structuring branches. For example, you normally want a designated branch which contains working and tested code, usually the _master_ branch. You might want another branch for developing new features. Or a branch for making critical fixes to production code. And so on...

We'll be using a branching model similar to the one described [here](http://nvie.com/posts/a-successful-git-branching-model/). You don't need to understand this in detail, since it won't really affect your day-to-day programming.

### Collaboration
If you were the only person working on a project, you'd be good to go now. (Un?)Fortunately you are not. There are nine other people on this project, which means that no matter how fantastic _you_ are at using source control, there's a 900% chance of someone else screwing up. Because that's what people do: Screw things up. Given the chance, _someone_ will merge premature code into the master branch. Or try to roll back a commit you've branched from. Or indent their code with tabs instead of spaces. Hell, they might even straight up nuke the repo by copy-pasting into the terminal from Stack Overflow. 

To stop this from happening we'll be using the _fork & pull_ model of collaboration, explained [here](https://help.github.com/articles/using-pull-requests/#types-of-collaborative-development-models) and [here](http://nathanhoad.net/git-workflow-forks-remotes-and-pull-requests).

#### Pull requests
Pull requests are what drive the collaboration process, and as such are important to understand. Luckily, it's really easy! Once you've pushed your work to your remote fork a nice green button with the text "Compare & pull request" will appear on your project's page. If you're happy with your code, click that button and I (Mac) will be notified that you want to merge code into the project. If your code is up to par (which it is, of course), it will be merged. If not, the team will tell you what you need fix, and you go fix it and repeat the process.

Again, [Github](https://help.github.com/articles/using-pull-requests/) has a really nice tutorial.

### Intermediate pep talk
You're basically a Github pro by now. You know how to set up ssh authentication on your machine. You're fluent in the language of repos, branches and commits. You know what a branching model is, and you can work with your teammates in a fork/pull fashion.

Well done. It's all downhill from here :)

