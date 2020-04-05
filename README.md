# vim-snippets-custom
Additional `Python` vim snippets for personal use.
These include:
* `deffa`: function or class method with type annotation
* `defa`: function with docstrings and type annotation
* `defca`: class method with docstrings and type annotation
* `defsa`: static method with docstrings and type annotation
* `goprop`: getter-only property with type annotation
* `gsprop`: getter-setter property with type annotation

# Requirements
These additional snippets are contained in a patch file for `vim-snippets`.
The required vim plugins are therefore:
* `SirVer/ultisnips`
* `honza/vim-snippets`

# Applying Patches
To apply the patches to `vim-snippets`, do the following:
1. Install the required plugins.
2. Change directory to `~/.vim/bundle/vim-snippets`.
3. Execute
    ```
    git am --signoff < path/to/patch_file
    ```
