# Questions

## What is pneumonoultramicroscopicsilicovolcanoconiosis?
### the max length of a word in the dictionary: 45

## According to its man page, what does `getrusage` do?
### returns resource usage measures for who, which can be for RUSAGE_SELF for the calling process, which is the sum of resources used by all threads in the process.
### RUSAGE_CHILDREN for all children of the calling process that have terminated and been waited for.
### RUSAGE_THREAD Return resource usage statistics for the calling thread.

## Per that same man page, how many members are in a variable of type `struct rusage`?
### 2 structs 14 longs = 16

## Why do you think we pass `before` and `after` by reference (instead of by value) to `calculate`, even though we're not changing their contents?

TODO

## Explain as precisely as possible, in a paragraph or more, how `main` goes about reading words from a file. In other words, convince us that you indeed understand how that function's `for` loop works.

TODO

## Why do you think we used `fgetc` to read each word's characters one at a time rather than use `fscanf` with a format string like `"%s"` to read whole words at a time? Put another way, what problems might arise by relying on `fscanf` alone?

TODO

## Why do you think we declared the parameters for `check` and `load` as `const` (which means "constant")?

TODO
