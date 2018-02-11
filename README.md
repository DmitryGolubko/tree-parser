# tree-parser
Simple tree viewer

## Description
Converts JSON tree into classic view and output it.

After each tree output, it is determined what action to perform

Criteria for actions with trees:

1. If the total sum of all nodes of the tree is more than 5000, then the tree is already old and it is necessary to cut it 
down.

2. If the maximum depth of the tree is more than 5, then the tree is too tall and it is necessary to cut it.

3. If the tree is not very tall and not very old - then leave it.
