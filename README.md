## Directories and files

### `data`

Holds the list of words used for the actual puzzle, `words.csv`, as well as the `process.py` script used to generate it. I did have to manually remove quite a few vulgar and offensive words from the SCOWL list. To use it, [create a customized word list](http://app.aspell.net/create) at the SCOWL website and provide the files as arguments.

### `img`

Holds the favicon and assorted vector images used throughout the puzzle.

### `js`

While I tried to separate functions into logical files, I did not do the best job. `words.js` has most of the functions related to word manipulation, such as scoring words. `interface.js` has functions related to the interface, which happens to be most of them. `main.js` has functions related to setup of new games as well as helpful utility functions.

### `main.html`, `styles.css`

These files make up the structure and styling of the project.
