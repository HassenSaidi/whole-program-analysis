# whole-program-analysis

This tool is inspired by the work on
[gllvm](https://github.com/SRI-CSL/gllvm), a whole program analysis
applying clang to all source files. Here, we replace clang by an
arbitrary command. Instead of producing a bitcode, the command
produces an arbitrary data file. Linking combiles object files, or in
the case of gllvm bitcode files. Here, the user defines how the files
produced by compilation phase are combined.