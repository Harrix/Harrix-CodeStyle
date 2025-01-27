---
tags: [Code style]
author: Anton Sergienko
author-email: anton.b.sergienko@gmail.com
lang: en
---

# Git style

## Prefixes

The prefixes for the names of commits:

- **➕ Add / Create**: something added
- **🚀 Build**: build project
- **🗑️ Delete / Remove**: delete something
- **📚 Docs**: documentation work
- **🧪 Experiment**: experiment that is not allocated to a separate git branch
- **🐛 Fix**: error correction
- **🔧 Modify**: any modification other than a fix
- **🚚 Move**: move files
- **♻️ Refactor**: refactoring code
- **✒️ Rename**: rename something to something
- **🔄 Replace**: replace something to something
- **✨ Style**: fix formatting, correcting typos
- **🎯 Test**: for testing
- **⬆️ Update**: update files (eg from another project)
- **🔙 Revert**: revert the last commit
- **🚀 Publish**: publish the article

## Rules

All commits must start with the specified prefixes.

Do not end the subject line with a period.

Do not use articles. Explanations: [link](https://www.reddit.com/r/git/comments/7gjhpd/using_an_article_in_a_commit_message/) and [link](https://english.stackexchange.com/questions/38759/dropping-articles-in-the-title-of-an-article-or-a-section-or-in-the-caption-o).

## Examples

```text
➕ Add CC BY 4.0 license
➕ Add empty line at end of file
➕ Add featured image for article ""
➕ Add function ...
➕ Add MIT license
➕ Add more information about ...
🚀 Build project
🚀 Build version 0.
➕ Create test.md
🗑️ Delete extra character is newline
🗑️ Delete extra spaces
🗑️ Delete unnecessary files
🗑️ Delete unnecessary imports
🗑️ Delete unnecessary lines in code
🗑️ Delete unnecessary sections
📚 Docs. Add license in markdown format
📚 Docs. Add range on copyright year
📚 Docs. Modify README.md
📚 Docs. Style. Correction docs
📚 Docs. Add docstring
🐛 Fix bug with ...
🐛 Fix figure captions
🐛 Fix punctuation errors
🐛 Fix spelling mistakes
🐛 Fix style error
🐛 Fix use of double quotes
🐛 Fix. Sentence must start with capital letter
🔧 Modify featured image. Use my own icon
🔧 Modify some parts of code
🔧 Modify. Comment out code
🔧 Modify. Here is description of code modifications
🔧 Modify. Optimize images
🔧 Modify. Transform GIF and MP4 to AVIF
🚚 Move files from folder '' to folder ''
🚀 Publish article
♻️ Refactor code
♻️ Refactor. Sort classes, methods, functions
🗑️ Remove dots and commas from filenames
✒️ Rename files
🔄 Replace hyphens with long dash
🔙 Revert "Experiment with definition lists"
✨ Style. Beautify code
✨ Style. Correction article
✨ Style. Correction code
✨ Style. Correction markdown file
✨ Style. Sort functions and classes
⬆️ Update files on new version
```
