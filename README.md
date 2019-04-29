# vim-inkscape-insert

The original repo can't work and eps is not supported by many markdown previewer. So I fix the bug and change the default format to png.

## Original docstring

A plugin to create and insert drawings (in .png format) in markdown files and 
edit them in inkscape without leaving vim.

The only command is 
`:Ink \<name of the graph you want to add\>`. It saves all 
the images created by the Ink command in the directory specified with 
`g:inkscape_graphs_dir` (default `./Images/`)

