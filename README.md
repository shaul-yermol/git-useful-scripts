# git-useful-scripts
Useful scripts for working with git

## Pre-requirements 
This scripts will work with and diff tool provided, but I recommend on using p4merge or beyond compare.

## git-diffadd - diff the changes and add them to the stage.
#### Usage: git-diffadd [path to folder]
This script will work on all unstaged changes, for each of these the diff will be shown, followed by a simple y/n confirmation to stage the changed file. Usefull for reviewing changes before staging them.

## git-timeplase - show a simplified time lapse view of a file changes.
#### Usage: git-timelapse [path to file]
This script will show a list of all commited changes for a file, followed by a prompts to select any 2 commits. When selected, the diff between these commits will be shown.
