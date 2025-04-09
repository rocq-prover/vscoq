### Language Server

The module [lspManager](lspManager.mli) implements the main SEL event `lsp`
which deals with LSP requests plus some VSRocq specific messages.

[vsrocqtop](vsrocqtop.ml) is a Rocq toplevel that initializes Rocq and then runs
a SEL loop for the `lsp` event.

