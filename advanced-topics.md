# Git-notes advanced topics
While git-notes are really simple to get started with, more advanced techniques can make them more effective.

# Public notes
Consider making one or more of you git-notes repos public, to share your knowledge with others.

## Making a repo public
A repo can be changed from private to public. For GitHub, see [Making a repository public](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/managing-repository-settings/setting-repository-visibility#making-a-repository-public).

## Adding a copyright or license
A copyright or license allows others to use your notes in ways that you intend, while protecting it from unauthorized uses.

Adding a copyright is as simple as adding the copyright symbol, the year, and your name to your README.md file. See [How Do I Correctly Format a Copyright?](https://info.legalzoom.com/article/how-do-i-correctly-format-copyright) for more infomation. If this document were copyrighted, it would look like:

```© 2021, DigitalReplica, LLC.```

Creative Commons](https://creativecommons.org/share-your-work/) offers several licenses to provide flexible ways to share your work.

Best practice is to add a file to your repository named ```LICENSE.txt``` to your repo with the license text in it. See [Licensing a repository](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository). Alternately, you can add your license as a snippet in your ```README.md``` file.

## Add a 'notes` topic
GitHub allowed each repo to be [classified with a topic](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/classifying-your-repository-with-topics). By tagging your notes with the [notes](https://github.com/topics/notes) topic, others can more easily find them.

## Add sponsors
GitHub adds a [sponsor button]https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/displaying-a-sponsor-button-in-your-repository) to your repo when the special file ```.github/FUNDING.yml``` is added. You can add your sponsorship links to provide ways to support your work.

# Private notes
Not all notes will be public, so this section explores different methods to either share private notes with a community, or make them totally private so only you can access.

## Private shared repos
Cloud git providers host the private source code for many companies, so they have some of the most secure software in the world: [GitHub](https://github.com/security), [GitLab](https://about.gitlab.com/security/), [Bitbucket](https://bitbucket.org/product/cloud-security).

GitHub
* [Create](https://docs.github.com/en/get-started/quickstart/create-a-repo) a private notes repository.
* [Add collaborators](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-user-account/managing-access-to-your-personal-repositories/inviting-collaborators-to-a-personal-repository)

## Private repos
Create a private repo, and don't give anyone access to it. Only you will be able to see the contents.

## Using private hosting
Hosting a private git server requires a bit more technical knowledge, but there are plenty of guides for how to do this. [Git on the Server](https://git-scm.com/book/en/v2/Git-on-the-Server-Setting-Up-the-Server) is a good starting point.

## Using other cloud storage providers
A git repository can be hosted in a folder of any cloud storage or file sharing mechanism. It can be kept completely private, or shared with others. It requires some git command line knowledge, and [Git Basics](https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository) is a good reference.

## Local or encrypted storage
The most secure method is using local storage, which can be your computer, a thumb drive, or file server. Encrypting the storage device before using adds additional security (but is beyond the scope of this guide.) Creating a local git repo is exactly the same as the cloud storage option, using the command line and [Git Basics](https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository) reference.

# Organizing notes
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


# git-knowledge
Once comfortable that git-notes is useful and working, take a look at [git-knowledge](https://github.com/digitalreplica/git-knowledge) for a method of linking multiple repos together into a larger knowledge system.
