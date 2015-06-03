# Dart Language Specification and Grammar

This project contains a [PDF](doc/dartLangSpec.pdf) of the latest **Dart Language Specification** whose sources are taken from @[dart-lang/sdk/docs/language][], as well as versions of the grammar that are automatically extracted from the specification.

Documents are contained in the [doc](doc) folder. The **grammar** is available in

- [markdown](doc/grammar-AUTOGENERATED-DO-NOT-EDIT.md). This is the most workable format; e.g., non-terminal symbols are _linked_. Here are direct links to some productions:
    - [_libraryDefinition_](doc/grammar-AUTOGENERATED-DO-NOT-EDIT.md#libraryDefinition)
    - [_partDeclaration_](doc/grammar-AUTOGENERATED-DO-NOT-EDIT.md#partDeclaration)
    - [_topLevelDefinition_](doc/grammar-AUTOGENERATED-DO-NOT-EDIT.md#topLevelDefinition)
- [text](doc/grammar-AUTOGENERATED-DO-NOT-EDIT.txt).
- [PDF](doc/grammar.pdf) (formatting is still work in progress).

The [latest language specification sources][dart-lang/sdk/docs/language] are mirrored in [DLS/current](DLS/current). Subfolders exist for the following key versions as well:

- [1.0](DLS/1.0)
- [1.3](DLS/1.3), corresponds to [ECMA-408 1st Edition][]
- [1.6](DLS/1.6), corresponds to [ECMA-408 2nd Edition][] (the current edition)
- [1.9](DLS/1.9)

[ECMA-408 1st Edition]: http://www.ecma-international.org/publications/files/ECMA-ST-ARCH/ECMA-408%201st%20edition%20June%202014.pdf
[ECMA-408 2nd Edition]: http://www.ecma-international.org/publications/files/ECMA-ST/ECMA-408.pdf
[dart-lang/sdk/docs/language]: https://github.com/dart-lang/sdk/tree/master/docs/language