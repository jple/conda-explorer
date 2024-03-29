# Description
This repo creates a html page containing all conda env packages.  
The generated page contains search bar to find packages in order to choose the proper env.

# Demo
[Demo here](https://jple.github.io/conda-explorer/demo/main.html)

# Features
- show all conda env with installed packages (including pip)
- search/filter list of packages from envs

# Requirements
- conda installed, with `conda` command available
- awk

Dependencies :
- [Choices.js 9.0.1](https://github.com/Choices-js/Choices)
- Languages : js, bash

# Usage
1. Create the html page `./show-env-content.sh > main.html`
2. Open it

# Todo
- hide env when no packages matched
- show how many packages are found / number of searched for each env
- sort env by number of packages found
- features : search by version
- issue : css breaks when search on
- issue : corr html (table in table)
- show users conda env
- add one-page option (include cat script.js, instead of importing)
