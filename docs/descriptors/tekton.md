---
title: TEKTON linters in MegaLinter
description: tekton-lint is available to analyze TEKTON files in MegaLinter
---
<!-- markdownlint-disable MD003 MD020 MD033 MD041 -->
<!-- @generated by .automation/build.py, please do not update manually -->
<!-- Instead, update descriptor file at https://github.com/oxsecurity/megalinter/tree/main/megalinter/descriptors/tekton.yml -->
# TEKTON

## Linters

| Linter                                                                                     | Additional                                                                                                                   |
|--------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|
| [**tekton-lint**](tekton_tekton_lint.md)<br/>[_TEKTON_TEKTON_LINT_](tekton_tekton_lint.md) | [![GitHub stars](https://img.shields.io/github/stars/IBM/tekton-lint?cacheSeconds=3600)](https://github.com/IBM/tekton-lint) |

## Linted files

- File extensions:
  - `.yml`
  - `.yaml`

- Detected file content:
  - `apiVersion: tekton`

## Configuration in MegaLinter

| Variable                    | Description                   | Default value |
|-----------------------------|-------------------------------|---------------|
| TEKTON_FILTER_REGEX_INCLUDE | Custom regex including filter |               |
| TEKTON_FILTER_REGEX_EXCLUDE | Custom regex excluding filter |               |

