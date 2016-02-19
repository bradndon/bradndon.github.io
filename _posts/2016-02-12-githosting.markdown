---
layout: post
title: Git Hosting, an Easy way to Collaborate with Git
date: 2016-02-12T12:30:20.000Z
categories: 491 Development
---
Introduction
============
Last week we talked about the basics of using git as a source control system.
Now we will look at ways to keep your code that is under source control located
in a centralized place instead of on your machine. The reason we would want this
is to be able to share your code easier with others as well as not relying on
your machine alone to store your code. While git can keep track of your changes
so that you do not forget the changes you make, if you lose your computer, you
will still lose all your code. We are going to look at three different options
to host your git projects: [Github][github], [BitBucket][bitbucket], and
[GitLab][gitlab].

Github
=========
The first hosting site we are going to look at is Github. Of these three, Github
is the most well known for its large collection of open source projects. One of
the main reasons for this is that it is free to use for open source projects.
Another advantage to Github is that a lot of employers look at potential
employees Github's to see what kind of projects they have created or contributed
on before. With Github being a large open source platform, there is a very good
platform for having many collaborators on a project. One major problem that
people have with Github is that there is not an easy way to handle the issues
that users have opened on a project. You can read more about that [here][deargh].

BitBucket
============
Another popular hosting site is Atlassian's Bitbucket. One major advantage over
Github is that it has free hosting for private repositories for teams five
people and under. This can be extremely helpful for teams that can not make their
source code public for various reasons. Another feature that I particularly like
is the side by side diffs that can show what has changed between commits. It makes
it easy to look back at past code and see the changes that were made. One final
item I enjoy about BitBucket is its easy integration with Atlassian's other
products JIRA and Confluence. These products are also good so being able to use
them with BitBucket can be advantageous to those already using them.

GitLab
=========
The final hosting site we will look at today is GitLab. This one is the most
generous with its pricing, as the community edition gets you unlimited free
private and public repositories for you to work with. Another advantage GitLab
gives you is the ability to largely customize the homepage of their project to
give it a little more flair and appeal. GitLab also keeps the source code for
their community edition as and open source project, the only one of these three
that has their hosting software source code available.

Conclusion
==========
All three of these solutions are popular for different reasons. While choosing
one may seem arbitrary, it will lead to you learning a lot about how to work
with them. I hope that this post will help you find out which one is right for
you.

[github]: https://www.github.com
[bitbucket]: https://www.bitbucket.org
[gitlab]: https://www.gitlab.com
[deargh]: https://github.com/dear-github/dear-github
