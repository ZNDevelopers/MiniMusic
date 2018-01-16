---
title: Contributing to MiniMusic
---

Do you want to help us create *MiniMusic*?

If your answer to that is "yes", then **great**!

However, there are a few things you’ll need to know before you get started.

Reporting Issues
================

If you have found an issue, you should report it to us so that we know about it.

We automatically get crash reports from the main *MiniMusic* program but not
from any of the other projects, and these also do not give us enough information
normally.

Using the GitHub Issues page
----------------------------

To report an issue, go to <https://github.com/ZNDevelopers/MiniMusic/issues> and
create a new issue. Follow the issue template for what to write.

Note: You should create an issue even if a crash report was sent to us.

Setting Up your Environment
===========================

It is very easy to get started contributing to *MiniMusic*.

Some prerequisites:
-------------------

-   Knowledge of C\# and/or C++ and WPF

-   An installation of [Visual Studio 2017](https://www.visualstudio.com/vs/)
    with the C\# and C++ bundles (Solution may work in earlier versions but no
    promises)

The Simple Steps
----------------

1.  Fork the *MiniMusic* repo (must use GitHub for this).

2.  Clone the fork to your computer.

3.  Make a branch, call it `dev/[your username]`. This branch is what you will
    make your changes into.

Working on Bugs or Features
===========================

1.  Find an issue to fix and assign yourself if no one else has been assigned,
    or make one for what you will work on and assign yourself.

2.  If you are working on a new issue or an issue that has no-one assigned, ask
    a contributor (with branch-creating permissions) to create a branch for the
    issue

3.  Write some code, fix some bugs, **but make sure it is relevant to the
    issue.**

4.  Check that your code is descriptive, follows the [style
    guide](https://d.docs.live.net/8e523da4f19ae759/STYLE_GUIDE.md) and has
    comments (but only where you cannot tell what’s happening from the code).

5.  Commit each file, give them descriptive messages that are shorter than 72
    characters each.

6.  Push the commits to your forked repo.

7.  Repeat from 6+ until you’ve got something that works. It doesn’t have to be
    finished, it just needs to work. Note: If you just want *Travis CI* to run
    tests on your code, make a pull request and call it `[NOMERGE] (pull
    request name)` where `(pull request name)` is a descriptive name of what
    you’ve done.

8.  Create a pull request from your dev branch to the issue’s branch. Read the
    [pull request template](PULL_REQUEST_TEMPLATE.md) for how to create the PR.
    Note: If it does not follow the template it will usually be denied.

Projects
========

As we use *Visual Studio*, there is one main solution in this file and many
projects. If you are making a new feature, ask yourself, “Is this part of
something that already exists or is it separate?” Because, if it is separate,
for example the *MiniMusic* language parser/compiler vs the *MiniMusic* GUI, a
new project should be created.
