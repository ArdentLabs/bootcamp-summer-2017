Week 1 - Hello World :wave:
===========================

 > `console.log('Hello World');`

## Course background and goals

This course is a jump into the deep end of mobile app development. Everything you learn in this class will be applicable to the real world, in a real job. Expectations for you will be high. Read the required resources that we give you, especially in the first few weeks. If you feel that you are falling behind, **please talk to us**. There will be several opportunities for acquiring additional assistance; you will find office hours and code reviews to be most helpful.

In addition to the amount of work, instructors will be strict on the way you write your code. Clean, reusable code is an essence of programming excellence and a main determining factor between a good and bad software engineer. Code reviews will also serve as instructors' way to find any stylistic hiccups and assess the structural integrity of your design.

## Project management

When your code base begins to grow, you'll find that it'll be harder to keep track of what you've done. It's inevitable. **Version controlling** is one way of cope with your code's **fate to become more complex**. By keeping track of all changes that you've made to your code, you'll be able to *jump* back in time to view your codebase as it was before. This makes it easier to quickly fix mistakes. In addition, you also have the opportunity to comment the changes to the code.

 > Read more about the difficulties of developing software in Frederick Brook's [No Silver Bullet](http://faculty.salisbury.edu/~xswang/Research/Papers/SERelated/no-silver-bullet.pdf) (optional)

#### Git
 > Git allows groups of people to work on the same documents (often code) at the same time, and without stepping on each other's toes. ([Try Git](try.github.io))

The most popular version control system of today is **Git**. As most of the tools that we will be using, it is used on the *command line*. I'll be going over some of the basic git commands here, but if you're on a Mac or Linux operating system, you can easily view the full documentation by executing `man git`.

[Install Git](https://git-scm.com/download) on your local machine before continuing.

 - Git works on the idea of a **repository**, a collection of code.
 - All changes to the code are encapsulated in a **commit**, which consists of a list of what you've changed and a description.
 - Collaborators can **pull** the repo to get the latest commits and **push** to upload any new commits they have made.

Git is designed to be *decentralized*; each user has their own local copy of the full version history. This allows you to decide who's repository you want to work with, allowing you to decide your **central repository**. Compare this with centralized version control systems (such as `svn`) that have a single, enforced central repository, whereas the version history is stored in a server-side repository.

 > Read more about how Git is decentralized in [this StackExchange question](https://softwareengineering.stackexchange.com/questions/315252/why-does-everyone-use-git-in-a-centralized-manner) (optional)

There's more to be learned, as `git` is a pretty complex command, but here are some basic commands that you'll need to know to get started.

Command | Description
------- | -----------
init    | Create a new repository (creates the `.git` directory)
status  | View the `diff` status of the repository
add     | Stage a file to be committed
commit  | Annotate the changes to the staged files **(BE DESCRIPTIVE)**
push    | Upload your commits for others
pull    | Get the latest commits


#### GitHub
 > [GitHub](https://github.com/) is a development platform inspired by the way you work.

The difference between Git and Github always confuses people at first. So I'll set it straight. You don't need GitHub to use Git. In no way does Git rely on Github, nor is it the official website for Git. GitHub is simply a **hosting service for Git repositories**. There are other hosting services for Git, such as [Bitbucket](https://bitbucket.org/) and [GitLab](https://gitlab.com/), but we're only going to be using GitHub since it's the most popular (but not always the best!)


#### Interactive Git demonstration
 > [Click here for the in-class demo](https://github.com/ArdentLabs/try-git)

#### Git flow
 > http://nvie.com/posts/a-successful-git-branching-model/

Once you've understood the basics of Git, now it's time we get a little fancy with it.

## Communication and coordination

#### Slack


#### Trello
 > Organize your project into cards.

Trello is a card-based project management application that allows developers to plan their project from start to finish. This is a great way to communicate with the team by letting them know what features you have planned out. Team coordination can also be simplified by utilizing card assignment to assign members to work on different features.

 > View a sample application board: https://trello.com/b/mXh5WQ9E

## Component design