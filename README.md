# fcitx5-vim
Auto-switch Fcitx5 on mode changes.

## Requirements
- Vim 9.0+ (with +job support)
- Fcitx5 (with fcitx5-remote)

## Setup

Get your input method ID

``` bash
fcitx5-remote -n
```

Add to your .vimrc like this

``` vim
let g:fcitx5_im = 'keyboard-us'
```
