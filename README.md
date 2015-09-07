# rplot: Make ggplot2 plots easily from the command line

License: MIT or GPL2, at your choice.

## Requirements:

- iterm2 2.9 or later (as of this writing, this means using a beta)
  - http://www.iterm2.com/downloads.html

- imgcat somewhere in your $PATH
  - https://raw.github.com/gnachman/iTerm2/master/tests/imgcat

- littler somewhere in your $PATH
  - http://dirk.eddelbuettel.com/code/littler.html
  - *Pay attention to the case-insensitive issues with OS X!*
  - This script assumes you installed littler as "lr". Change it accordingly
    if that's not the case

## Minimal example

    $ rplot 'ggplot(mtcars, aes(x=cyl, y=mpg)) + geom_jitter()'
