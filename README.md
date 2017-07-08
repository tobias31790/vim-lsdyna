# vim-lsdyna
[VIM](http://www.vim.org/) filetype plugin for [Ls-Dyna](http://www.lstc.com) FE solver.

## Introduction

What is Ls-Dyna filetype plugin?

It's just bunch of scripts to speed up work with Ls-Dyna keyword file and VIM text editor.

## Main features
- Syntax highlighting
- Folding
- Keyword library
- Useful mappings, functions and commands

### Syntax highlighting
With color syntax it's easier to navigate through a keyword file.

![syntax](https://raw.github.com/wiki/gradzikb/vim-lsdyna/gifs/syntax.gif)

### Folding
Node & element table folding, no more never ending scrolling!

![folding](https://raw.github.com/wiki/gradzikb/vim-lsdyna/gifs/folding.gif)

### Keyword library
With keyword library you can very quick add a new Ls-Dyna keyword into your model.

![libraryb](https://raw.github.com/wiki/gradzikb/vim-lsdyna/gifs/omni-completion.gif)


### Commands
The plugin has many build-in commands to work with data directly for:
- curves
- nodes
- elements

![commands](https://raw.github.com/wiki/gradzikb/vim-lsdyna/gifs/commands.gif)


### Commands, functions & mappings
The plugin has couple of great functions to make your work even faster:
- mappings
- comment/uncomment
- data line autoformating
- keyword text objects

## Example

The plugin in action you can see [here](https://www.youtube.com/watch?v=5a62UACiBA0&feature=youtu.be).

## Documentation

The plugin has decent [documentation](https://github.com/gradzikb/vim-lsdyna/blob/master/doc/lsdyna.txt) with detail explanation of all functions and examples.

Please read the documentation before you start using the plugin.

`:help lsdyna`

## Installation

[Pathogen](https://github.com/tpope/vim-pathogen)

```
cd ~/.vim/bundle
git clone https://github.com/gradzikb/vim-lsdyna
```

## License

The GNU General Public License

Copyright &copy; 2014 Bartosz Gradzik
