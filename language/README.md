---
id: move-language
title: Move Language
custom_edit_url: https://github.com/libra/libra/edit/master/language/README.md
---

# Move

The Move language directory consists of five parts:


## How is this folder organized?

```
├── README.md          # This README
├── benchmarks         # Benchmarks for the Move language VM and surrounding code
├── bytecode-verifier  # The bytecode verifier
├── e2e-tests          # Infrastructure and tests for the end-to-end flow
├── functional_tests   # Testing framework for the Move language
├── compiler           # The IR to Move bytecode compiler
├── stdlib             # Core Move modules and transaction scripts
├── test.sh            # Script for running all the language tests
└── vm
    ├── cost-synthesis # Cost synthesis for bytecode instructions
    ├── src            # Bytecode language definitions, serializer, and deserializer
    ├── tests          # VM tests
    └── vm-runtime     # The bytecode interpreter
```
