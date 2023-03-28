# What is versioning?

Hello, friend! I assume you already know programming basics and even use some kind of versioning, but not know about it.
In this section you will get acquainted with Git, Github, Merge requests and how we do this in Mitigate way.

Let's imagine the problem. You working with very difficult project, a lot of code lines and anti patterns. At some moment, you starting to generate reserve copies of your files and folders. And vuala...

![Your beautiful structure](/test-github-pages/assets/images/awfull-naming.png)

You get into situation when you have many folders with partly working project and no working project at all. And worst, to understand difference between them you need to review all code from first line to the end.

Okay, maybe you are a other type of person, what holds only one folder... With comments.

![Your dutiful code](/test-github-pages/assets/images/terrible-comments.jpg)

But again it is not best way to review *history of changes*

Let's imagine other situation, you working not alone, but with your classmate Tom. Tom is a nice guy, have some experience in programming, but Tom not know what kind of person you really are... You both modified same files and now someone need to *merge changes* together. You even don't know how many line of code Tom changed...

![You with bestie](/test-github-pages/assets/images/pr-approve.jpg)

# What is Git, Svn and Mercury?

It could be very awesome if you could get some backstory for Tom code lines, like short *explanation* for code blocks or classes what added to project. Maybe, world is in need for this feature and only you can help! But before you start making plans, let's assume you, what this kind of tools already exists. Like GIT, SVN and Mercury.

We don't have your classmate Tom at work, but we have +5 developers per one project and each one generating or changing code on daily basis. Usually we use Git in our projects.

Git allow use to
1. List history of changes (even for one file)
![Commits list](/test-github-pages/assets/images/good-commits-example.png)
2. Review changed code, author and date
![Commit](/test-github-pages/assets/images/commit-changes.png)
3. Make separate branches (like project versions) and merge them together
4. Return back old code by reverting commit
5. Search code parts in commits history even if this code not present in project.

# What is Github?

Another service what help us to develop projects is Github. Website where you can place your code for public use, what allows all developers to access it and modify.

All popular open source projects are holding there:
[Rails](https://github.com/rails/rails)
[Vue](https://github.com/vuejs)
[Hanami](https://github.com/hanami/hanami)

Git + Github are developer most basic things to know.
These tools eases developer daily routine.

You will know them better in next sections.