# Motivation

Vim is a text editor. It has been maintained by Bram Moolenaar for over [30
years](https://web.archive.org/save/https://www.simplethread.com/vim-at-30-heres-why-its-still-relevant/)
with its first release dated 12-NOV-1991. It's a modal editor that was designed
to support syntax highlighting, navigation keybindings, macros,
multi-window/multi-tab editing with a powerful configuration system and
functionality extensible with plugins. Recently, an intrepid wave of
next-generation engineers have decided to attempt rewriting Vim to support Lua
scripting (in addition to Vimscript). It adds a number of user-facing features,
but it's main value-add is for developers in the Vim ecosystem: better
language-server support, better API documentation and versioning practices. It
aims to be a drop-in replacement for Vim.

Vim is not an IDE. However, its plugin support has been (ab)used to introduce
IDE-like features for Go including language server support, jump to definition,
tooltip information, autocomplete. You can find a list of recommended plugins
for a variety of editors and IDEs on the official [golang
repo](https://github.com/golang/go/wiki/IDEsAndTextEditorPlugins).


# Plugins

## [vim-go](https://github.com/fatih/vim-go)
### Features
  - Functions that test, compile, or install the working project.
  - Syntax highlighting and code folding.
  - Delve support.
  - Language server integration
  - Formatting
  - Jump to token
  - View documentation
  - Import management
  - Refactoring tools (rename)
  - Linting integration (error reporting)
  - Snippets

## [Syntastic](https://github.com/vim-syntastic/syntastic)
  - Linting

Note: Can provide formatting if external tools are installed and a linter which
supports formatting is used.

## [tagbar](https://github.com/preservim/tagbar)
  - Jump to token

## [vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go)
  - Compile
  - Error reporting

## [vim-godef (Deprecated)](https://github.com/dgryski/vim-godef)
  - Jump to token

## [vim-go-extra](https://github.com/vim-jp/vim-go-extra)
  - View documentation
  - Formatting

* Note: Hasn't been updated in >5 years.

## [go-ide](https://github.com/plentiform/go-ide)
  - File browser (`fzf`) 
  - Jump to token (`vim-go`)
  - Autocompletion (`ncm2/ncm2-go` and `stamblerre/gocode` (deprecated))
  - Snippets (`Ultisnips`)
  - Debugger (`vim-go`)
  - Import management (`vim-go`)
  - Formatting (`vim-go`)

* Note: `neovim`-only, apparently. Has a lot of dependencies including `python`
  (`pynvim`) and `nerdfonts`. Has not been touched in >15 months.

## [govim](https://github.com/govim/govim)

