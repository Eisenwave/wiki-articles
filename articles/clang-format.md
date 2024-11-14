# Formatting Code Automatically With Clang-Format

Formatting code (indentation, braces, etc.) consistently can be difficult,
especially for large projects with many collaborators.
You can format C and C++ code with **[clang-format][it]** automatically.

Usually, you create a `.clang-format` file in your project
to set [formatting options][options]:
```yml
BasedOnStyle: Google   # choose a base style (if any)
IndentWidth: 4         # choose your own options
# ...
```

## See Also

- [Formatting options in **Visual Studio**][vs]
- [Formatting options in **VSCode**][vsc]
- [Clang-Format in **CLion**][clion]


[it]: https://clang.llvm.org/docs/ClangFormat.html
[options]: https://clang.llvm.org/docs/ClangFormatStyleOptions.html
[vs]: https://learn.microsoft.com/en-us/visualstudio/ide/reference/options-text-editor-c-cpp-formatting
[vsc]: https://code.visualstudio.com/docs/cpp/cpp-ide#_code-formatting
[clion]: https://www.jetbrains.com/help/clion/clangformat-as-alternative-formatter.html
