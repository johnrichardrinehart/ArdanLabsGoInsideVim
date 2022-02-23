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
