# git-stager

git-stager lets you easily add/remove files to/from the index.  It shows the working tree status as per `git status --short`.  You can move around the entries toggling files in and out of the index with a single key.

git-stager supports these keys:

- `g` or `H` - Move to the first entry
- `M` - Move to the middle entry
- `G` or `L` - Move to the last entry
- `j` - Move down one entry
- `k` - Move up one entry
- `o` - Open the current file
- `SPACE` or `ENTER` - Add an unstaged file or remove a staged file
- `q` or `ESCAPE` - Quit


## Installation

git-stager requires Ruby.

Copy the `git-stager` script to your path and make it executable (e.g. `chmod 755 git-stager`).

git-stager is not installable as a Ruby gem.

