# Underflow Theme for Vim
![drag](https://i.imgur.com/dbSQZgW.png)

Note that these colors were chosen with 256-bit color in mind. This is my
first contribution on github, so if something isn't working, please let
me know.

---

## Installation

**Vim Plug or other plugin managers:**
Open your `vim.rc` files, and within the area of adding plugins, add
`Plug: 'HenryNewcomer/vim-theme-underflow'`.

Now scroll down past the `plug#end()` area and add:

    colorscheme underflow
    set background=dark
    syntax on

If using another plugin manager, such as Vundle, the steps are appropriately
similar for the first part. The second part is the same. Just reference your
plugin manager's manual for further assistance on what syntax to use for
automatically installing plugins.

## Manual Installation
Linux/Mac OS) If on a Unix-based OS, simply clone/save this and place it in your
 `~/.vim/colors/` directory (assuming you haven't changed this path).

Next, open, your `.vimrc` file and add:

    colorscheme underflow
    set background=dark
    syntax on

Note that if you have a plugin manager and are using the manual installation,
you will most likely have to add the three commands *after* your plugin's closing
method. For example, if using Vim Plug, you'd add the lines after `plug#end()`.

---

If you have any questions, feel free to e-mail me at a.cliche.email@gmail.com

*I haven't included a license, yet, but these files are free to use as you see
fit, as long as you don't claim to take credit for the original file.*
