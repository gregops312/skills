---
name: go
description: TBD
disable-model-invocation: true
---

# Design
- Use a global variable for the name of the CLI for help and docs
- Use a variable for the name of the command in the file
- Use best practices for design and implementation

# Documentation

- Do not write dedidcated docs for every feature
- Write key overviews of features into README.md

# Makefile

- Do not write dedicated makefile cmds for each test
- Allow passing a var to the make test for a specific test with the -run flag
