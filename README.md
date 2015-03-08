# Monokai2 Color Scheme for Vim

Monokai2 is a Vim port of the monokai theme for TextMate originally created by Wimer Hazenberg.

By default, it has a dark gray background based on the version created by Hamish Stuart Macpherson for the E editor.

![Gray Background](http://i.imgur.com/Sx1bRUH.png)


256-Color terminals are also supported, though there are some differences with the Gui version. Only the dark gray background style is supported on terminal vim at this time.

## Installation

Copy the file on your .vim/colors folder.
If you are using [pathogen]() plugins managert then install it this way:

```zsh
  cd ~/.vim/bundle
  git clone https://github.com/kajamite/vim-monokai2.git
```  

and then in vimrc set theme:

```vim
  colorscheme monokai2
```

If you prefer the scheme to match the original monokai background color, put this in your .vimrc file: 
```
let g:monokai_original = 1
```

There is also an alternative scheme under development for color terminals which attempts to bring the 256 color version as close as possible to the the default (dark) GUI version. To access, add this to your .vimrc:
```
let g:rehash256 = 1
```

