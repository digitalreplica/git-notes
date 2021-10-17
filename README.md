# Git-notes Introduction
Git-notes is a simple notes system using markdown and git. While git is traditionally a developer tool, it's really simple for anyone to use.

1. Create an account on one of the git cloud providers, such as [GitHub](https://github.com/), [GitLab](https://about.gitlab.com/), or [Bitbucket](https://bitbucket.org/)
2. Create a [git repository](https://docs.github.com/en/get-started/quickstart/create-a-repo) to store notes in.
3. Edit (or create) the README.md file and start adding notes.

Note: Examples are shown using [GitHub](https://github.com/), but any version of cloud or local git works equally well.

Let's break down the steps in more detail.

## Notes are stored in a git repository
A git repository (or repo for short), is simply a collection of files. All changes to files are tracked (like turning on ```Track Changes``` in a document.) The contents of the repo are completely up to you. This guide focuses on how to use a repo for human readable notes.

A template is available to make it even easier to start. If you're using GitHub, open [git-notes-template](https://github.com/digitalreplica/git-notes-template) and click the ```Use this template``` button. With other cloud providers, you can [git clone](https://github.com/git-guides/git-clone) the template repository, or copy-paste the file contents.

When created, a repo must be set as a public or private repo, meaning that other can see it, or only you can. If in doubt, set it to private. It can easily be changed to public later.

## Notes are markdown
[Markdown](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) is a human-focused text format, easily readable and writable by anyone. It was created as a way to make web pages without knowing html, so has almost all the features of most word processors.

Markdown files have the extension ```.md``` at the end of the filename. Many file editors recognize markdown files, and can automatically show a preview while you're editing with all the formatting applied.

When browsing your note repo through a web browser, git cloud providers automatically display markdown files as web pages with all formatting applied. So you can use your repo as your personal web page. And the special file ```README.md``` is automatically displayed when viewing the repo in a web browser. That makes this file perfect for a home page, introduction, or table of contents.

One handy markdown feature is [links](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#links) for linking to other web pages, or using relative links to other notes in your repo. For example, the link to the [advanced topics](advanced-topics.md) note is written like ```[advanced topics](advanced-topics.md)```.

## Use the built-in editor
GitHub has a built-in file editor. For an existing file, find the ```pencil``` icon to edit that file. To create a few file, click the ```Add file``` menu button and select ```Create new file```. Name the file, ending with the extension ```.md```.

## Saving new work is called a commit
Saving new changes to one or more files is called a [commit](https://github.com/git-guides/git-commit), and is part of the git change tracking feature. Each commit requires a commit message, which is simply a description of what's changed. This be as short or long as you like, and GitHub automatically suggests a commit message when changing a single file.

# You're ready
That's all you need to effectively use the git-notes system.

# Advanced topics
Once comfortable taking notes, see [advanced topics](advanced-topics.md) for additional ways to share, protect and organize notes.

# Resources
Here are other resources and note taking systems that may be helpful.

## Zettelkasten
Niklas Luhmann created a paper-based "Zettelkasten" method of organizing notes, using a numbering system to link them well before the internet was even invented.
[Getting Started • Zettelkasten Method](https://zettelkasten.de/posts/overview/)

## Links
[Build the Perfect Productivity System with Paper Notebooks and Digital Tools](https://zapier.com/blog/digital-and-paper-note-taking-systems/)

https://betterhumans.pub/zettelkastens-3-note-taking-levels-help-you-harvest-your-thoughts-58326840f969
* 3-tiers:
  * fleeting notes: thoughts and ideas during the day
  * literature notes: what you learn from others
  * permanent notes: digested prose
* lots of links to more references
* mentions "Roam". Looks like the [Roam Research](https://roamresearch.com/) at $15/mo

https://notes.andymatuschak.org/About_these_notes
* wow, immense resource
* "garage door up" system of note taking
* “Knowledge and productivity are like compound interest.”
