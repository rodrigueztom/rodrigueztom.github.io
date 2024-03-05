---
layout: archive
title: "Tips for GitHub and Vim"
permalink: /ghvim/
author_profile: true
---
## Github

I would generally always start by creating a GitHub repository.
Then to copy an existing git directory

```bash
git clone <SSH URL>
```

To pull changes from remote:

```bash
git pull <remote> <branch>
```

To push all changes to remote:

```bash
git add .
git commit -m 'COMMIT MESSAGE HERE'
git push <remote> <branch>
```

## Vim

To open and edit a file in the same directory where the current file is:

```
:e %:h/filename
```
