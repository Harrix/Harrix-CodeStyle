---
tags: [Code style]
author: Anton Sergienko
author-email: anton.b.sergienko@gmail.com
lang: en
---

# Git style

## Prefixes

The prefixes for the names of commits:

- **Add / Create**: something added
- **Build**: build project
- **Delete / Remove**: delete something
- **Docs**: documentation work
- **Experiment**: experiment that is not allocated to a separate git branch
- **Fix**: error correction
- **Modify**: any modification other than a fix
- **Move**: move files
- **Refactor**: refactoring code
- **Rename**: rename something to something
- **Replace**: replace something to something
- **Style**: fix formatting, correcting typos
- **Test**: for testing
- **Update**: update files (eg from another project)
- **Revert**: revert the last commit
- **Publish**: publish the article

## Rules

All commits must start with the specified prefixes.

All commits related to the documentation should start with `Docs` with its description (but this is not necessary). But if the repository itself is documentation, the prefix `Docs` in the commit names is not needed.

Do not end the subject line with a period.

Do not use articles. Explanations: [link](https://www.reddit.com/r/git/comments/7gjhpd/using_an_article_in_a_commit_message/) and [link](https://english.stackexchange.com/questions/38759/dropping-articles-in-the-title-of-an-article-or-a-section-or-in-the-caption-o).

## Examples

```text
Add empty line at end of file
Add CC BY 4.0 license
Add featured image for article ""
Add function ...
Add MIT license
Add more information about ...
Create test.md
Build project
Delete extra spaces
Delete extra character is newline
Delete unnecessary files
Delete unnecessary lines in code
Delete unnecessary sections
Remove dots and commas from filenames
Docs. Add license in markdown format
Docs. Add range on copyright year
Docs. Modify README.md
Docs. Style. Correction docs
Fix bug with ...
Fix figure captions
Fix punctuation errors
Fix spelling mistakes
Fix style error
Fix use of double quotes
Fix. Sentence must start with capital letter
Modify featured image. Use my own icon
Modify some parts of code
Modify. Comment out code
Modify. Here is description of code modifications
Move files from folder '' to folder ''
Refactor code
Rename files
Replace hyphens with long dash
Style. Beautify code
Style. Correction article
Style. Correction code
Style. Correction markdown file
Update files on new version
Revert "Experiment with definition lists"
Publish article
Refactor. Sort classes, methods, functions
```
