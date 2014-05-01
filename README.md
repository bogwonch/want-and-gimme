# Want and Gimme

A set of implicit make file rules to get me what I want.

## Usage

To build the file `outputfile.pdf`:

~~~~{.sh}
want outputfile.pdf
~~~~

To build all possible files with the suffix `.pdf`:

~~~~~{.sh}
gimme pdf
~~~~~

## Install

~~~~{.sh}
ln -s $PWD/makerules $HOME/.makerules
~~~~
