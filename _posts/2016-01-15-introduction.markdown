---
layout: post
title: Introduction to the series
date: 2016-01-15T12:30:20.000Z
color: 2196F3
categories: 491 Development
---
Hello!
======
Welcome to my blog! For the next few weeks, I will be writing five blog posts
on development tools. Most of what I will cover will be collaborative tools.
What this means is tools that you can use to ease the accessibility of adding
team members to a project you are working on. In a professional environment,
you will be required to collaborate with others and you may see some or all of
the tools I will cover. It is much easier to get along with a team when
everything is running smoothly and you can focus on working together. I have
found most of these tools to be useful even for personal projects, as they can
help you keep your projects organized and make it easier to return to them at
any time.

What we will learn
==================
Throughout these five weeks we will learn a lot of hopefully useful information
in topics such as creating virtual machines so that everyone is working in the
same environment, using version control, and using a collaborative chat tool so
that you can all work remotely. I wanted to write on these topics because I
think it is part of the development cycle that many students do not learn about
during their time studying. These tools may seem at first like they are
unnecessary for aspiring professionals since they are not directly related to
programming, but they can be extremely helpful.

For example, lets say you know the production server you will be working on
will be running Linux while your home machine will be running Windows. It can
be frustrating to have to try and port your code once you have it working on
one machine so we can use a virtual machine to develop your project as if you
are on a Linux machine. You can also set it up so that other people can easily
create the same virtual machine as you so that you are all on the same page. If
all of this sounded confusing, do not worry, I will be taking us step by step
through the setting up process and some basic applications these tools can be
used for.

Another common problem that you will run into is how to share code with multiple
people while you are all editing. Because this is very common, there are many
solutions out there to solve this such as [Git][git] and [Subversion(SVN)][svn].
These platforms can seem intimidating at first, but as you use them, they
become more simple. I will cover how to use these on a basic level but also
some collaborative uses such as merging, which is usually not taught when
teaching a basic understanding of these tools.

The five posts will be laid out as follows:

1. Virtual Machines: What are they and how can they help?

2. Vagrant: A simpler way to use VM's

3. Git: Source control is a necessity!

4. Git Hosting: An easy way to collaborate with Git

5. Project Management: Some tools to help stay organized.

What we will not learn
======================
Although we will be learning about these tools to aid our development, we will
not actually be learning any programming or developing skills. By this I mean
that any code samples that are not relevant to the lesson will not be explained,
just provided, so that we can focus on the tool itself, instead of a random
piece of code. In the same light, we will not be learning about different
operating systems, if you would like to follow my examples but run a different
VM for example, the commands given will not necessarily work on that operating
system.

How the posts will be formatted
===============================
Each post will be in a tutorial style, so that you can easily follow along step
by step without getting lost. Whenever discussing something that is inside the
computer, like a file directory, will be shown like this: `/bin`. For easy
understanding, all code snippets needed for the test projects that we go
through will be highlighted like so:
{% highlight bash %}
telnet towel.blinkenlights.nl
{% endhighlight %}
Any time I talk about a new technology tool, or person, I will link to the main
page for that specific item. For example, this blog is being written as part of
 my senior project series at [Western Washington University][wwu] taught by
 [Aran Clauson][aran].

[aran]: https://cse.wwu.edu/computer-science/aran
[git]: https://git-scm.com/
[svn]: https://subversion.apache.org/
[wwu]: http://wwu.edu
