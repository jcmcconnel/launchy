Launchy
======

A shortcut system for the BASH shell.

Intended primarily to make it easier to deal with emulation and compatibility layers, like DOSBox and Wine.

Will operate differently depending on the value of `$0`, so to use the full range of capability make symbolic links to the script:

   - dos
   - win
   - launch

etc.

Also includes a very basic [and in alpha state] bundling feature, where a directory containing a `.launchrc` can be invoked with `launch [DIR]` and the shortcut in the `.launchrc` file will be run.
