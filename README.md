# First Programming Language

First is a **functional-first programming language** that emphasizes pure functional programming while providing **controlled access to imperative features**. It features a strict distinction between pure functions and side-effecting interactions, strong typing with TypeScript-like expressiveness, and Haskell-style type classes.

**First is currently only available on macOS** and can be installed via [Homebrew](https://brew.sh): `brew tap akkeshavan/first && brew install --HEAD first-compiler`. 

You may  clone and build the project on Linux, but has not been tested yet. There is no installable available for Linux yet

## Key Features

- **Functional-first**: Primary programming paradigm emphasizing pure functions
- **Controlled imperative**: Imperative features (mutable state, loops) restricted to interaction functions
- **Strong typing**: Static type checking with comprehensive type inference
- **Advanced type system**: Supports refinement types, dependent types, union types, intersection types, and more
- **Haskell integration**: Seamless integration with Haskell libraries through automatic wrapper generation
- **Effect isolation**: Mutable state and loops are restricted to interaction functions only
 

## Language Principles

- **Pure functions by default**: Functions are pure unless explicitly marked as interactions
- **Explicit side effects**: Side effects are contained within interaction functions
- **Immutable by default**: Variables are immutable unless explicitly marked as mutable
- **Effect isolation**: Mutable state and loops are restricted to interaction functions only

---

## Homebrew install ( Mac only)
```bash
brew tap akkeshavan/first
brew install --HEAD first-compiler
```

## Clone the examples ( this repo)

 ```bash
   git clone https://github.com/akkeshavan/first-book.git
   cd first
   ```

   ## Run all examples
 
   ```bash
   ./examples/run-all-brew.sh
   ```   

 

This runs the compiler unit tests and (if enabled) runtime tests. You can also run the compiler test executable directly:

```bash
./build/bin/test_compiler
```

 ## Cloning and building the compiler

You can access the source code to the first language specifications and compiler here. So far =it has been built only for MacOS. You may try to build and test these examples on other platforms. The repo has instructions on how to build and run the compiler.
[First language source code](https://github.com/akkeshavan/first)