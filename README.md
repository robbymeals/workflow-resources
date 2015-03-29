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
syntax on
filetype plugin indent on
colorscheme zellner
let &colorcolumn="80,".join(range(120,999),",")
set nowrap
autocmd BufNewFile,BufReadPost *.md set filetype=markdown
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

### useful one-liners

### general software engineering
