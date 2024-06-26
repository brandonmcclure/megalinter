---
title: BICEP linters in MegaLinter
description: bicep_linter is available to analyze BICEP files in MegaLinter
---
<!-- markdownlint-disable MD003 MD020 MD033 MD041 -->
<!-- @generated by .automation/build.py, please don't update manually -->
<!-- Instead, update descriptor file at https://github.com/oxsecurity/megalinter/tree/main/megalinter/descriptors/bicep.yml -->
# BICEP

## Linters

| Linter                                                                                      | Additional                                                                                                           |
|---------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|
| [**bicep_linter**](bicep_bicep_linter.md)<br/>[_BICEP_BICEP_LINTER_](bicep_bicep_linter.md) | [![GitHub stars](https://img.shields.io/github/stars/Azure/bicep?cacheSeconds=3600)](https://github.com/Azure/bicep) |

## Linted files

## Configuration in MegaLinter

| Variable                   | Description                                     | Default value |
|----------------------------|-------------------------------------------------|---------------|
| BICEP_PRE_COMMANDS         | List of bash commands to run before the linters | None          |
| BICEP_POST_COMMANDS        | List of bash commands to run after the linters  | None          |
| BICEP_FILTER_REGEX_INCLUDE | Custom regex including filter                   |               |
| BICEP_FILTER_REGEX_EXCLUDE | Custom regex excluding filter                   |               |

