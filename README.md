 ## Double Threaded Binary Search Tree

 Goals: Understand the implementations of a Threaded Binary Search Tree: to add a target node, delete a target node, search for a node, find the depth of the tree, clear all the nodes the tree and to use it's threads to traverse through the tree.


## Included Files

- `InorderIterator.cpp` and `InorderIterator.h`: definitions and functions for inorder traversal of tree

- `ThreadedBST.cpp` and `ThreadedBST.h`: Definitions for Threaded Binary Tree

- `main.cpp`: Runs all tests

- `output.txt` : output from `./simple.compile.sh > output.txt 2>&1`
showing  how the program is compiled and run

- `simplecompile.sh': Unix bash script file to compile, run, and the delete the executable. can use to create an output.txt file

## Compile and Run

```
./simplecompile.sh
```

### Style Explanation
These options are defined in `.clang-tidy` file.

Perform all check except the following:

-fuchsia-* do not need specific checks for "fuchsia" a modular, capability-based operating system
- cppcoreguidelines-pro-bounds-array-to-pointer-decay: do not give warnings on assert
- google-build-using-namespace: for simplicity allow `using namespace std;`
- google-readability-braces-around-statements: allow compact code without `{`
- readability-braces-around-statements: allow compact code without `{`
This option is not available in CSS Linux lab under LLVM 3.8.1, but is needed on my PC when using 9.0.0
- hicpp-no-array-decay need to use assert
- modernize-use-trailing-return-type: not ready yet for `auto func() -> int` format
- hicpp-braces-around-statements: allow compact code without `{` (this option
- cppcoreguidelines-pro-bounds-pointer-arithmetic,
- llvm-header-guard: not using full directory name
- google-global-names-in-headers: for simplicity allow `using namespace std;`
- cppcoreguidelines-special-member-functions: not defining move operator
- hicpp-special-member-functions: not defining move operator
- cppcoreguidelines-owning-memory: not using gsl


### Work divided
Shushmitha:
- implementation 50%
- design : 50%
- testing 50%

Melaney:
- implementation  50%
- design: 50%
- testing: 50%



