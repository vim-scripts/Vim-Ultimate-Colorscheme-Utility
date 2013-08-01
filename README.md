vim-ultimate-colorscheme-utility
================================

Vim plugin that enables colorscheme browsing, choosing favorites, and automatic/manual scheme switching based on the current filetype.
You no longer have to settle for one favorite scheme.

Features
========
Ultimate Colorscheme Utility offers several features for customizing your colorscheme preferences.
- Allows for easy browsing of all installed colorschemes, <br /> 
  see the awesome archive at https://github.com/flazz/vim-colorschemes for a ton of colorschemes.
- Allows saving favorite colorschemes for all vim, or for specific filetypes.
- Enables automatic switching of colorschemes when switching fietype buffers so that a favorite scheme is always on.

Required Vim Options
====================
Vim must have been compiled with the following features:
- modify\_fname

Installation
============

### via Pathogen, the preferred method

```bash
cd ~/.vim/bundle
git clone https://github.com/biskark/vim-ultimate-colorscheme-utility.git
```

### via archive, the bad method
1. download archive
2. unzip archive into .vim

### via Vundle, the unknown method
1. I don't use Vundle, but I assume it's similar to Pathogen

Quick Usage
===========
Note: All mappings are customizable, view the helptags for more information.

```vim
<leader><leader>a    " Adds the current colorscheme to favorites
<leader><leader>A    " Removes the current colorscheme to favorites
<leader><leader>f    " Goes to next colorscheme in favorites
<leader><leader>F    " Goes to previous colorscheme in favorites
<leader><leader>n    " Goes to next colorscheme in all colors
<leader><leader>N    " Goes to previous colorscheme in all colors
<leader><leader>q    " Views all favorites
```