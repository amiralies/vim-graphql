# graphql.vim

[![Build Status](https://travis-ci.org/jparise/vim-graphql.svg)](https://travis-ci.org/jparise/vim-graphql)

This is a vim plugin that provides [GraphQL][gql] file detection and syntax
highlighting.

## Installation

### Using [Plug][plug]

1. Add `Plug 'jparise/vim-graphql'` to `~/.vimrc`
2. `vim +PluginInstall +qall`

### Using [Vundle][v]

1. Add `Plugin 'jparise/vim-graphql'` to `~/.vimrc`
2. `vim +PluginInstall +qall`

### Using [Pathogen][p]

1. `cd ~/.vim/bundle`
2. `git clone https://github.com/jparise/vim-graphql.git`

[gql]: https://facebook.github.io/graphql/
[p]: https://github.com/tpope/vim-pathogen
[plug]: https://github.com/junegunn/vim-plug
[v]: https://github.com/gmarik/vundle

## Testing

The test suite uses [Vader.vim](https://github.com/junegunn/vader.vim). To run
all of the tests from the command line:

    $ make test
