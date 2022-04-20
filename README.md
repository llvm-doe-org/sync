# Sync branches from DoE llvm-project fork

This repository is used to trigger github actions to sync branches 
from the llvm-project DoE fork with the upstream repository. 

List of synced branches: 


| Local branch                   | Upstream branch       | Action file                                                                     | Schedule     | Status |
| ------------------------------ | --------------------- | ------------------------------------------------------------------------------- | ------------ | ------ |
| llvm-project/llvm.org/main     | llvm-project/main     | [sync-llvm-project-main.yml](.github/workflows/sync-llvm-project-main.yml)      | */30 * * * * | ![llvm-project/llvm.org/main status](https://github.com/llvm-doe-org/sync/workflows/Sync%20llvm-project/llvm.org/main/badge.svg) |

| llvm-project/doe               | llvm-project/main     | [sync-llvm-project-doe.yml](.github/workflows/sync-llvm-project-doe.yml)        | */30 * * * * | ![llvm-project/doe status](https://github.com/llvm-doe-org/sync/workflows/Sync%20llvm-project/doe/badge.svg) |
| llvm-test-suite/llvm.org/main  | llvm-test-suite/main  | [syn-llvm-test-suite-main.yml](.github/workflows/sync-llvm-test-suite-main.yml) | */30 * * * * | ![llvm-test-suite/llvm.org/main status](https://github.com/llvm-doe-org/sync/workflows/Sync%20llvm-test-suite/llvm.org/main/badge.svg) |
