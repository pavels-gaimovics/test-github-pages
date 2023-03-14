# Git, GitHub

# Agenda
1. What is versioning?
2. Why we use them?
3. What is Git, Svn and Mercury?
4. What is github?


Hello, friend! I assume you already know programming basics and even use somekind of versioning, but not know about it.
In this section you will get acquainted with Git, Github, Merge requests and how we do this in Mitigate way.

Let's imagine the problem. You working with very difficult project, a lot of code lines and anti patterns. At some moment, you starting to generate reserve copies of your files and folders. And vuala...

![Your beutiful structure](/test-github-pages/assets/images/awfull-naming.png)

You get into situation when you have many folders with partly working project and no working project at all. And worst, to understand difference between them you need to review all code from first line to the end.

Okay, maybe you are a other type of person, what holds only one folder... With comments.

![Your beutiful code](/test-github-pages/assets/images/terrible-comments.png)

But again it is not best way to review *history of changes*


Let's imagine other situation, you working not alone, but with your classmate Tom. Tom is a nice guy, have some experience in programming, but Tom not know what kind of person you really are... You both modified same files and now somone need to *merge changes* together. You even don't know how many line of code Tom changed...

![You with bestie](/test-github-pages/assets/images/pr-approve.png)

It could very awesome if you could get some backstory for Tom codelines, like short *explanation* for code blocks or classes what added to project? Maybe, world is in need for this feature and only you can help! But before you start, let's assume you, what this kind of tools already exists. And one of them