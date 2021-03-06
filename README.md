![Welpe Colorwheel](img/colorwheel.png)

WELPE.vim 
===========

Dark colorscheme for vim, with a mixture of bright, saturated highlights
and pale, low-key colors for non-keyword syntax groups. Uses excusively colors from the 256-color-range, so it should look identical in gvim and vim.

## PALETTE

![black](img/_black.png) `black #080808 (232)`

![gray1](img/_gray1.png) `gray1 #1c1c1c (234)`

![gray2](img/_gray2.png) `gray2 #262626 (237)`

![gray3](img/_gray3.png) `gray3 #3a3a3a (233)`

![darkred](img/_darkred.png) `darkred #870000 (88)`

![maya](img/_maya.png) `maya #87afff (111)`

![mediumorchid](img/_mediumorchid.png) `medium orchid #af5fd7 (134)`

![moss](img/_moss.png) `moss #afd7af (151)`

![paleturqoise](img/_paleturquoise.png) `pale turquoise #afffff (159)`

![roman](img/_roman.png) `roman #d75f5f (160)`

![orange](img/_orange.png) `orange #ffaf00 (214)`

![shalimar](img/_shalimar.png) `shalimar #ffffaf (229)`

![gray10](img/_gray10.png) `gray10 #808080 (244)`

![gray21](img/_gray21.png) `gray21 #dadada (253)`

![white](img/_white.png) `white #eeeeee (255)`

![truewhite](img/_truewhite.png) `truewhite #ffffff (15)`

## PREVIEW

![GVIM preview 1](img/welpeGVIM_preview.jpg)
![GVIM preview 2](img/welpeGVIM_preview2.jpg)


## INSTALLATION

#### via vundle

`Plugin 'tstelzer/welpe.vim'`

`:PluginInstall`

#### via vimplug

`Plug 'tstelzer/welpe.vim'`

`:PlugInstall`

#### manual download

- place [tstelzer/welpe.vim/master/colors/welpe.vim](https://raw.githubusercontent.com/tstelzer/welpe.vim/master/colors/welpe.vim) in `~/<yourvimdir>/colors/`
- if you want lightline support, place [tstelzer/welpe.vim/master/autoload/lightline/colorscheme/welpe.vim](https://raw.githubusercontent.com/tstelzer/welpe.vim/master/autoload/lightline/colorscheme/welpe.vim) in `~/<yourvimdir>/autoload/`

#### enable colorscheme

add the following line *after* `:syntax enable`

`colorscheme welpe`

#### using lightline?

find your lightline settings and add `'colorscheme': 'welpe',` to the top, like:

```
let g:lightline = {
    \ 'colorscheme': 'welpe',
    // more lightline settings
```

#### additional options

all-bold

`let g:welpe_all_bold = 1`

use italics

`let g:welpe_use_italics = 1`

## KNOWN 'BUGS'

- 8 and 16 terminal colors might not work for now

## TODO

#### plugin

- [X] Lightline
- [ ] better NERDtree colors
- [X] readable diff colors (native + fugitive)

#### shortterm

- [X] HTML
- [X] CSS / SASS
- [ ] JS

#### longterm
*as I'm not coding in these, might take a while ...*

- [ ] C-family
- [ ] Python
