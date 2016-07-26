---
layout: post
title:  "Do you want to know how to use Git?"
disqus_id: 1234
categories: Git
---

Knowing how to use Git and understanding what is happening when you're typing commands is something that I find a very important asset. This tutorial with illustrations will try to give you a better better understanding about what is actually happening.

## Why we need Git
The most powerful asset about using Git is that you can fuck up as much as you want, you can experiment, and if it doesn't work you can just go to a previous version. What I see happening a lot of the time is that people are afraid to commit something. This is because they don't know to revert their changes.

Another reason why Git is great is that it allows us to work together. We know exactly who commited what code, so if we don't understand a specific piece of code we know who to go to. We can work on one project at the same time. And when we have conflicts we just merge them together "said no one ever". But it's true that if you know what <<<< --- >> means that it gets a lot easier to solve the merge.

## Why learning about Git is such a bother
It can be really hard to understand what is happening! It's a very abstract concept. When I just started to use Git I was in a constant state of "I have no idea what I'm doing". Just getting the code appear on github was good enough at that moment. If we don't like solving merge conflicts, starting a branch, working with multiple people on a project then that is a sign that we don't know how to wield the powers of Git

## What this tutorial will teach you
I will try to explain the basics of Git with an analogy, something that we know. In this case it will be "Building a snowman". I use illustrations to visualise the process. I recently read an interesting article about how we can only learn about what we know so by using an analogy you will definitely get a better understanding of the process. The bijbehorende terminal commands will be included with every part. If you want to know why I made this decission then you can read about it in my other blog post "Why I use the terminal".
So the topics will be:
- Creating a commit
- Do a push
- Do a pull
- Resolving merge conflicts

There are a lot of other things that I think are really useful to know, so I will make a part 2 of this tutorials that I consider more advanced.
- Working with branches
- Local vs Remote

### Setting up a git repository
{% highlight sh %}
$ git init
{% endhighlight %}

### Creating a commit
{% highlight sh %}
$ git add --all
{% endhighlight %}

{% highlight sh %}
$ git commit -m "Hello this is a messsage to tell you I'm worked on this and that"
{% endhighlight %}

{% highlight sh %}
$ git add --all
{% endhighlight %}

### Do a push
{% highlight sh %}
$ git push
{% endhighlight %}

### Do a pull
{% highlight sh %}
$ git pull
{% endhighlight %}

### Resolving merge conflicts
//todo

## Parting words
I hope this tutorials was able to give you a better understanding about how Git works.
If you have the time I would appreciate it if you could give some feedback about this tutorial.
My goals is to process more abstract topics in tutorials that are easy to understand. I use illustrations to help with this process.
