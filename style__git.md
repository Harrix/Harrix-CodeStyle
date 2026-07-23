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
- **🐞 Fix**: error correction
- **🔧 Modify**: any modification other than a fix
- **🚚 Move**: move files
- **♻️ Refactor**: refactoring code
- **✒️ Rename**: rename something to something
- **🔄 Replace**: replace something to something
- **✨ Style**: fix formatting, correct typos
- **⚗️ Test**: for testing
- **⬆️ Update**: update files (eg from another project)
- **🔙 Revert**: revert the last commit
- **🚀 Publish**: publish the article
- **🔀 Merge**: merge branches

## Rules

All commits must start with the specified prefixes. Icons can change.

Do not end the subject line with a period.

Do not use articles. Explanations: [link](https://www.reddit.com/r/git/comments/7gjhpd/using_an_article_in_a_commit_message/) and [link](https://english.stackexchange.com/questions/38759/dropping-articles-in-the-title-of-an-article-or-a-section-or-in-the-caption-o).

## Examples

```text
➕ Add annotations for
➕ Add CC BY 4.0 license
➕ Add empty line at end of file
➕ Add featured image for article ""
➕ Add featured image for article ""
➕ Add MIT license
➕ Add more information about
🎬 Add movie ""
🎬 Add series "" (season )
💤 Add dreams
💭 Add quotes from ""
📖 Add section "" in .md
⚗️ Add test for
⚠️ Add TODO
🚀 Build project
🚀 Build version 0.
➕ Create test.md
🗑️ Delete extra spaces
🗑️ Delete unnecessary files
🗑️ Delete unnecessary imports
🗑️ Delete unnecessary lines in code
🗑️ Delete unnecessary sections
📚 Docs. Add license in markdown format
📚 Docs. Add range on copyright year
📚 Docs. Fix
📚 Docs. Modify README.md
📚 Docs. Style. Correct docs
📚 Docs. Add docstring
📚 Docs. Add docstrings and annotations for
📚 Docs. Update
🐞 Fix annotations
🐞 Fix bug with ...
🐞 Fix punctuation errors
🐞 Fix ruff check issues
🐞 Fix ty check issues
🐞 Fix Cursor ai check issues
🐞 Fix Harrix PyLib check issues
🐞 Fix spelling mistakes
🐞 Fix spelling and punctuation mistakes
🐞 Fix. Sentence must start with capital letter
🔧 Modify some parts of code
🔧 Modify. Comment out code
📥 Modify. Download images
🔧 Modify. Here is description of code modifications
🖼️ Modify. Optimize images
🔧 Modify. Transform GIF and MP4 to AVIF
🔠 Modify. Translate
🚚 Move files from folder '' to folder ''
🚀 Publish article
♻️ Refactor code
📶 Refactor. isort, ruff format, sort, make docs in PY files
📶 Refactor. Sort classes, methods, functions
📶 Refactor. Sort sections
✒️ Rename files
🔄 Replace hyphens with long dash
🔙 Revert "Experiment with definition lists"
✨ Style. Beautify code
✨ Style. Beautify MD files
✨ Style. Beautify MD and regenerate g.md
✨ Style. Correct article
✨ Style. Correct code code
✨ Style. Correct markdown file
✨ Style. Fix ruff check issues
✨ Style. Update docstrings to Markdown format
⬆️ Update files on new version
📦 Update combined notes
⬆️ Update packages
📜 Update TOC

# ⚠️ TODO
```
