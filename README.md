
# ✨ Inspired Github

<p align="center">
  <img src="/screenshots/php.png" />
</p>

When I read [Taylor Otwell](https://github.com/taylorotwell)'s "How I Work" [medium post](https://medium.com/@taylorotwell/how-i-work-october-2018-edition-e66a09931e7f) (back in 2018) I fell in love with the theme he was using - Inspired Github color scheme for Sublime by [Seth Lopez](https://github.com/sethlopezme). I was using that theme ever since. When I moved to Vim I wasn't able to use it anymore so I made a port for it. Enjoy!

## Installation

```
Plug 'mvpopuk/inspired-github'
```

## Contributing

I work as a back-end PHP developer so my main focus was PHP and the syntax highlight for the stack I work with (PHP, blade, javascript, vue, html, css). PR's are highly appreciated. ✌

## Terminal Themes
I mostly use Kitty so a [kitty theme](/inspired-github.conf) is available. I also made the same [theme available for iTerm2](inspired-github.itermcolors). 

## Config

#### Lualine

<p align="center">
  <img src="/screenshots/lualine.png" />
</p>

If you want the same `lualine` config as the one in the screenshots you can copy / paste or modify [my config file](/config/lualine.lua). Please note that if you're using iTerm and a line height more than 100, the separators will not be correctly shown so you can use [these separators](https://github.com/mvpopuk/inspired-github.vim/blob/main/config/lualine.lua#L51) instead.

#### Tmux

<p align="center">
  <img src="/screenshots/tmux.png" />
</p>

I also created a minimal [tmux theme](inspired_github.tmux.conf) to match the overall look and feel of the theme. For more tmux configs check [my dotfiles](https://github.com/mvpopuk/dotfiles/blob/main/tmux/.tmux.conf)

#### Bufferline

If you're using `bufferline` you can find [the highlights I am using](https://github.com/mvpopuk/inspired-github.vim/blob/main/config/bufferline.lua#L33) to integrate the plugin with the theme.

## Screenshots

<p align="center">
  <span>PHP</span>
  <img src="/screenshots/php.png" alt="PHP" />
</p>

<p align="center">
  <span>Blade</span>
  <img src="/screenshots/blade.png" alt="Blade" />
</p>

<p align="center">
  <span>CSS</span>
  <img src="/screenshots/css.png" alt="CSS" />
</p>

<p align="center">
  <span>VUE & HTML</span>
  <img src="/screenshots/vue.png" alt="Vue & HTML" />
</p>
