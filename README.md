# vim-snippets-custom
Additional vim snippets for personal use

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
