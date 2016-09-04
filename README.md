# Go: Tree Building

Refactor a tree building algorithm.

Some web-forums have a tree layout, so posts are presented as a tree. However
the posts are typically stored in a database as an unsorted set of records. Thus
when presenting the posts to the user the tree structure has to be
reconstructed.

Your job will be to refactor a working but slow and ugly piece of code that
implements the tree building logic for highly abstracted records. The records
only contain an ID number and a parent ID number. The ID number is always
between 0 (inclusive) and the length of the record list (exclusive). No record
has a parent ID lower than its own ID and no record, except the root record,
has a parent ID that's equal to its own ID.

The tests are written using the `testing` package in the standard library.

To run a test file use the `go test` command:

    go test

# Source

This exercise is from the [Go][go] track on [Exercism][exercism]

[exercism]: http://exercism.io
[go]: http://exercism.io/languages/go



