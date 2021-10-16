# Git-notes 101
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

When browsing your note repo through a web browser, git cloud providers automatically display markdown files as web pages with all formatting applied. So you can use your repo as your personal web page.

Lastly, the special file ```README.md``` is automatically displayed when viewing the repo in a web browser. That makes this file perfect for a home page, introduction, or table of contents.

## Use the built-in editor
GitHub has a built-in file editor. For an existing file, find the ```pencil``` icon to edit that file. To create a few file, click the ```Add file``` menu button and select ```Create new file```. Name the file, ending with the extension ```.md```.

## Saving new work is called a commit
Saving new changes to one or more files is called a [commit](https://github.com/git-guides/git-commit), and is part of the git change tracking feature. Each commit requires a commit message, which is simply a description of what's changed. This be as short or long as you like, and GitHub automatically suggests a commit message when changing a single file.

# You're ready
That's all you need to effectively use the git-notes system.

## Consider which license to use
Especially with public repositories, consider what license to use. This can be traditional copyright. The [Creative Commons](https://creativecommons.org/share-your-work/) licenses provide many other ways to share your work.

## Consider adding 'notes` topic
GitHub allowed each repo to be [classified with a topic](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/classifying-your-repository-with-topics), so others can find it more easily. Consider tagging all git-notes repos with the topic [notes](https://github.com/topics/notes)

# git-notes 201
This section looks on how to organize notes within a git-notes repo. It's very much a work in progress, with multiple approaches being tried. Read through these principals and see what works.

## Recall is everything
The most important thing is asking, "What will I need to remember in order to find this again?" Can the idea be refined down to a single word? Two words? That is how repos and files should be named.

## One Repo per Concept
Each git-notes repo should encompass a single concept, containing all notes pertaining to that concept. At first, this can be a simple repo like my-notes. But people are multifacted, so as notes grow, it can be helpful to split notes into additional repos. Keeping each repo focused on a specific topic helps to know where to put notes, and where to find them.

## Prefer larger, fewer files
Notes are at first a quick way to remember things, then a dumping ground of everything related to a topic. But hopefully what emerges is an ever more organized understanding of it. That process takes time and editing, which is easier to to in a single file.

GitHub automatically displays files named `README.md`, which makes this file the natural starting point.

When a topic gets too large and unwieldy, has gone through several revisions in a single file, break the largest sections off into their own notes file. Create a new markdown file (ending in `.md`), move the section into it, and create a link in the original file.

## Densely link topics
Linking makes it easier to hop from topic to topic, idea to idea. It reinforces recall through repetition.

TODO: markdown linking examples.

## Prefer flat file structures
When creating new note files, keep them all in the same directory when possible. This makes linking much easier and helps prevent over-organization.

## Prefer unchanging note filenames
Changing the filename of a note breaks links and recall. It's an indication that ideas haven't matured fully in larger files, or distilled into the right keywords for recall.

## Don't over organize
Organization is an organic, evolving process. It's going to take multiple attempts and many changes to get it right. Following the principals of larger, fewer files and succinct recall keywords lets that happen with the least disruption.

# Security and privacy
Git repos are built for both sharing and security, since most companies use them for their secret source code. One can provide different levels of access and security for each repo, such as:

**Public**: Anyone can read the content.

**Privately Shared**: Access is restricted to a group of members, where those members can only read the content, or update as well.

**Private**: Only you have access.

**Local**: The files can only be accessed on a single computer, like storing files locally with the change tracking features of git.

**Encrypted**: Storing the files on an encrypted drive, or encrypting before storing in the git repo, provides the ultimate security.

# git-knowledge
Once comfortable that git-notes is useful and working, take a look at [git-knowledge](https://github.com/digitalreplica/git-knowledge) for a method of linking multiple repos together into a larger knowledge system.

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
