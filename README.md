# workflow-resources

### ssh
1. `ServerAliveInterval`: prevent remote boxes from kicking you out of sessions
    1.  http://www.howtogeek.com/howto/linux/keep-your-linux-ssh-session-from-disconnecting/

### vim
1. most of my .vimrc:
```vim
set tabstop=4
set expandtab
set softtabstop=4
set shiftwidth=4
set background=dark
set nu
set exrc "enable working directory vimrc files
set secure "restrict commands in wd vimrc files
syntax on
filetype plugin indent on
colorscheme zellner
let &colorcolumn="80,".join(range(120,999),",") "highlight after 80width
set nowrap "no text wrapping
autocmd BufNewFile,BufReadPost *.md set filetype=markdown "md files markdown
highlight LineNr term=bold cterm=NONE ctermfg=DarkGrey ctermbg=NONE gui=NONE gui
fg=DarkGrey guibg=NONE "change color of line numbers
```
1. I use pathogen on my local machine to manage plugins: 
    1. https://github.com/tpope/vim-pathogen

### useful command line tools
1. `screen`: 
    1. https://www.gnu.org/software/screen/
    1. http://aperiodic.net/screen/quick_reference
1. `pandoc`: http://johnmacfarlane.net/pandoc/
1. `moreutils`: http://joeyh.name/code/moreutils/
  1. `sponge`
  1. `vipe`
1. `less -S`: really useful alternative to `more` for scanning long text files 
1. `gdal` and `ogr2ogr`: useful opengis tools
    1. `sudo apt-get install libproj-dev`  
    1. https://milkator.wordpress.com/2014/05/06/set-up-gdal-on-ubuntu-14-04/:w
### useful one-liners

### general software engineering

