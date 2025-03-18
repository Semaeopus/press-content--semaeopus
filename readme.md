# Example Static Content Repo For Wiki Instances
![Arcetypal Repo](archetypal-heading.jpg)
1. Sync Markdown content into `content` directory to be consumed by private Wiki Instance.

*workflow*
```
on:
    repository_dispatch:
        types:
            - TRIGGER_BUILD
```
### Frontmatter
Current available fields:
```
---
description: SEO powers for wiki specific page
published: true # also defaults to true (sets visibility)
pin: 1111 # will lock page privately behind a hash
tags: ['blog']
---
```

---
## Welcome to Community content

This would be a community facing **public** repo.
Rules and regs in order to submit PRs
