folding (in vim-markdown):
	The following commands are useful to open and close folds:
		- `zr`: reduces fold level throughout the buffer
		- `zR`: opens all folds
		- `zm`: increases fold level throughout the buffer
		- `zM`: folds everything all the way
		- `za`: open a fold your cursor is on
		- `zA`: open a fold your cursor is on recursively
		- `zc`: close a fold your cursor is on
		- `zC`: close a fold your cursor is on recursively
	Try `:help fold-expr` and `:help fold-commands` for details.

tabs:
    :tabn       // go to next tab, also, Ctrl-PgDn
    :tabp       // go to prev tab, also, Ctrl-PgUp
    gt          // normal mode
    gT          // normal mode
    To open in tabs:
        gvim -p *.txt

Forked plugins
    +peaksea - a color plugin
            see current scheme with:
                :color
            change scheme:
                :colorscheme peaksea
    +set_tabline - customized tab line. Sets the tab title, including tab number  
    +vim-irblack-forked - a version of Infinite Red's vim theme; see README
                :colorscheme ir_black
    +vim-peepopen - fuzzy search of filenames and paths in a project; not sure how to use this yet



MRU
NERDtree


