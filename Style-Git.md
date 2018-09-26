# Style Git

## Prefixes

The prefixes for the names of commits:

* **Add** — something added.
* **Delete** — delete something.
* **Modify** — any modification other than a fix.
* **Fix** — error correction.
* **Style** — fix formatting, correcting typos.
* **Refactor** — refactoring code.
* **Test** — for testing.
* **Experiment** — experiment that is not allocated to a separate git branch.
* **Update** — update files (eg from another project).
* **Move** — move files.
* **Replace** — replace something to something.
* **Rename** — rename something to something.
* **Build** — build project.
* **Docs** — documentation work.

## Rules

All commits must start with the specified prefixes.

All commits related to the documentation should start with `Docs` with its description. But if the repository itself is documentation, the prefix 'Docs' in the commit names is not needed.

Do not end the subject line with a period.

## Examples

```text
Add function ...
Delete unnecessary files
Delete unnecessary lines in the code
Style. Correction code
Style. Beautify code
Fix bug with ...
Fix punctuation errors
Fix spelling mistakes
Fix style error
Modify some parts of the code
Update the files on the new version
Refactor code
Modify. Here is a description of the code modifications
Move files from folder '' to folder ''
Rename files
Build project
Docs. Style. Correction docs
Docs. Modify README.md
Docs. Add range on the copyright year
Docs. Add license in markdown format
Delete extra spaces
Delete the extra character is a newline
Replace the hyphens with a long dash
Fix. The sentence must start with a capital letter
Fix figure captions
Fix the use of double quotes
Delete an empty line at the end of the file
```