# tree-sitter-rcl

This repository contains the [Tree-sitter][tree-sitter] grammar for [RCL][rcl].

This repository is based on files extracted from the main repository available
at the following remotes:

 * <https://github.com/ruuda/rcl>
 * <https://codeberg.org/ruuda/rcl>

The upstream source of truth for the grammar is the `grammar/tree-sitter-rcl`
directory in the main repository. Because some tools that work with Tree-sitter
expect the grammar to live in a separate repository, the files have been
exported here. This repository also includes files generated by `tree-sitter
generate --build`, so that users do not need to have nodejs installed locally to
generate the parser. The main repository does not include those generated files.

For more information about hacking on the grammar, see
[the Tree-sitter chapter][rcl-ts] in the RCL documentation.

[rcl]:         https://rcl-lang.org/
[tree-sitter]: https://tree-sitter.github.io/tree-sitter/
[rcl-ts]:      https://docs.ruuda.nl/rcl/tree_sitter/
