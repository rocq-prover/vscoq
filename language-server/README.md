# VSRocq Language Server

This is a language server for Rocq speaking LSP with a few additional messages
which are VSRocq specific (e.g. declaring a point of interest, printing goals).

- [SEL](sel/) is a simple event library used to handle I/O
- [DM](dm/) is a document manager for Rocq with support for delegation via SEL
- [vsrocqtop](vsrocqtop/) is a Rocq toplevel speaking LSP based on DM and SEL
