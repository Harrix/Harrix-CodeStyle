# Style Git

## Prefixes

The prefixes for the names of commits:

* **Add** — something added.
* **Build** — build project.
* **Delete** — delete something.
* **Docs** — documentation work.
* **Experiment** — experiment that is not allocated to a separate git branch.
* **Fix** — error correction.
* **Modify** — any modification other than a fix.
* **Move** — move files.
* **Refactor** — refactoring code.
* **Rename** — rename something to something.
* **Replace** — replace something to something.
* **Style** — fix formatting, correcting typos.
* **Test** — for testing.
* **Update** — update files (eg from another project).

## Rules

All commits must start with the specified prefixes.

All commits related to the documentation should start with `Docs` with its description. But if the repository itself is documentation, the prefix 'Docs' in the commit names is not needed.

Do not end the subject line with a period.

## Examples

```text
Add function ...
Build project
Delete an empty line at the end of the file
Delete extra spaces
Delete the extra character is a newline
Delete unnecessary files
Delete unnecessary lines in the code
Docs. Add license in markdown format
Docs. Add range on the copyright year
Docs. Modify README.md
Docs. Style. Correction docs
Fix bug with ...
Fix figure captions
Fix punctuation errors
Fix spelling mistakes
Fix style error
Fix the use of double quotes
Fix. The sentence must start with a capital letter
Modify some parts of the code
Modify. Comment out code
Modify. Here is a description of the code modifications
Move files from folder '' to folder ''
Refactor code
Rename files
Replace the hyphens with a long dash
Style. Beautify code
Style. Correction code
Update the files on the new version
```