## Pages structure:

You can use this document to better understand the layout used on the manual pages, or if you plan to create new pages for personal use or for a pull request.

```

## Previous page: [[page]]                                                      // Previous page in [[...]], depending on where it is placed in the index (not to be confused with the previous block).
# Chapter x: Chapter title                                                      // If this is the chapter’s first page in the index.
### Page description.                                                           // A short description of the page content, always ending with a period (.).
## Main block                                                                   // Remember to place a block reference as a child of the page in the index. It is usually a large block covering a general topic that contains other sub-blocks.
  ### Block description.                                                        // Similar to the page description, is a short description of the block content, always ending with a period (.). It must be indented one tab ⇥ from the main block so it is connected to it.
  ***Sub-block***                                                               // A term, a list item, or a specific topic. It must be indented one tab ⇥ from the main block so it is connected to it.
    Sub-block description                                                       // The description of a sub-block, explaining the topic or describing the term or list item. It must be indented one tab ⇥ from the sub-block so it is connected to it, and therefore two tabs ⇥ from the main block.
  ### Important sub-block that contains other sub-blocks                        // If the list is very large and contains many sub-blocks, you can use ### to create an important sub-block. It must be indented one tab ⇥ from the main block so it is connected to it.
    ***Sub-block of the Important sub-block***                                  // Works similarly to the sub-block. It must be indented one tab ⇥ from the important sub-block so it is connected to it, and therefore two tabs ⇥ from the main block.
      Sub-block description                                                     // Identical to the other sub-block descriptions, but remember to use the tabs ⇥ correctly. It must be indented one tab ⇥ from the sub-block so it is connected to it, therefore two tabs ⇥ from the important sub-block and three tabs ⇥ from the main block.
## Next page: [[page]]                                                          // Next page in [[...]], depending on where it is placed in the index.

```
