Kit
===

Implement Otto using mostly bash, json, and lots of Hashicorp tools.
Instead of Appfile, use Blockfile.json.  

A kit is a combination of blocks that is easy to construct and
customize.  A kit is also a block.  A block maps to a git repository.
A block's fit to other blocks is determined by file conventions like
`script/bootstrap`, `Gemfile`, etc.

A kit uses a board, which is also a block, to provide services over
different environments so that generic deploys, orchestration, builds
can work.
