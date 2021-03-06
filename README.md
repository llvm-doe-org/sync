# Sync branches from DoE llvm-project fork

This repository is used to trigger github actions to sync branches 
from the llvm-project DoE fork with the upstream repository. 

List of synced branches: 


| Local branch | Upstream branch | Action file                                          | Schedule     | Status |
| ------------ | --------------- | ---------------------------------------------------- | ------------ | ------ |
| main         | main            | [sync_main.yml](.github/workflows/sync_main.yml)     | */30 * * * * | ![Main](https://github.com/llvm-doe-org/sync/workflows/Sync%20main%20branch%20with%20llvm/llvm-project/badge.svg) |
| doe          | main            | [sync_doe.yml](.github/workflows/sync_doe.yml)       | */30 * * * * | ![Doe](https://github.com/llvm-doe-org/sync/workflows/Sync%20doe%20branch%20with%20llvm/llvm-project/badge.svg) |
| ALCF         | main            | [sync_anl.yml](.github/workflows/sync_anl.yml)       | */30 * * * * | ![ALCF](https://github.com/llvm-doe-org/sync/workflows/Sync%20main%20branch%20@ANL%20with%20llvm/llvm-project/badge.svg) |
