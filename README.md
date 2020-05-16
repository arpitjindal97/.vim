# dotfiles

This repo contains my dotfiles. Use below command to get started quickly

    cd ~
    git clone https://github.com/arpitjindal97/dotfiles.git dotfiles
    cd dotfiles
    make install

## Prerequisite

Install below tools first before cloning the repo

- `zsh`
- `xsel` or `xclip` (only Linux)
- `vim` (prefer `gvim`)
- `tmux`

## Fonts

- [github.com/romkatv/powerlevel10k-media/MesloLGS NF](https://github.com/romkatv/powerlevel10k-media/)
- [github.com/belluzj/fantasque-sans](https://github.com/belluzj/fantasque-sans)

## Tools Used

- [termite](https://github.com/thestinger/termite/)
- [urxvt](http://software.schmorp.de/pkg/rxvt-unicode.html)
- [vim](https://github.com/vim/vim)
- [tmux](https://github.com/tmux/tmux)
- [zsh](https://github.com/zsh-users/zsh)
- [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh)
- [powerlevel10k](https://github.com/romkatv/powerlevel10k)

## Update configuration

To make your dotfiles in sync with mine, use the below command. It will fetch from upstream here.

    cd ~/dotfiles
    make update

## Screenshot

![screenshot](screenshot.png?raw=true)

## Plugins used in Vim

- [github.com/scrooloose/nerdtree](https://github.com/scrooloose/nerdtree)
- [github.com/Xuyuanp/nerdtree-git-plugin](https://github.com/Xuyuanp/nerdtree-git-plugin)
- [github.com/elzr/vim-json](https://github.com/elzr/vim-json)
- [github.com/vim-airline/vim-airline](https://github.com/vim-airline/vim-airline)
- [github.com/vim-airline/vim-airline-themes](https://github.com/vim-airline/vim-airline-themes)
- [github.com/airblade/vim-gitgutter](https://github.com/airblade/vim-gitgutter)
- [github.com/tpope/vim-fugitive](https://github.com/tpope/vim-fugitive)
- [github.com/ctrlpvim/ctrlp](https://github.com/ctrlpvim/ctrlp.vim)
- [github.com/jiangmiao/auto-pairs](https://github.com/jiangmiao/auto-pairs)
- [github.com/tpope/vim-surround](https://github.com/tpope/vim-surround)
- [github.com/Yggdroot/indentLine](https://github.com/Yggdroot/indentLine)
- [github.com/ntpeters/vim-better-whitespace](https://github.com/ntpeters/vim-better-whitespace)
- [github.com/altercation/vim-colors-solarized](https://github.com/altercation/vim-colors-solarized)
- [github.com/fatih/vim-go](https://github.com/fatih/vim-go)
- [github.com/godlygeek/tabular](https://github.com/godlygeek/tabular)
- [github.com/mhinz/vim-signify](https://github.com/plasticboy/vim-markdown)
- [github.com/darfink/vim-plist](https://github.com/darfink/vim-plist)

## Keybindings

### Tmux

| Key Combination | Function                           |
| --------------- | --------                           |
| prefix          | C-a                                |
| prefix + \[     | copy-mode vi                       |
| prefix + b      | previous-window                    |
| prefix + n      | next-window                        |
| prefix + p      | paste buffer from clipboard (xsel) |
| prefix + k      | select pane -U                     |
| prefix + j      | select pane -D                     |
| prefix + h      | select pane -L                     |
| prefix + l      | select pane -R                     |
| prefix + C-h    | resize pane -L 1                   |
| prefix + C-j    | resize pane -D 1                   |
| prefix + C-k    | resize pane -U 1                   |
| prefix + C-l    | resize pane -R 1                   |
| prefix + r      | reload source file                 |
| copy-mode-vi v  | begin-selection                    |
| copy-mode-vi y  | copy-buffer to clipboard (xsel)    |

Rest all other key binding are samme. I am also using [hdaly/tmux-better-mouse-mode](https://github.com/hdaly/tmux-better-mouse-mode) plugin for easy mouse movements

### Vim

| Key | Function           |
| --- | --------           |
| C-n | NerdTreeToggle<CR> |

I haven't set any key binding for vim. All the commands are as default provided by the plugins. Check their documentation. 


