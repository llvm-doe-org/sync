# Sync branches from DoE llvm-project fork

This repository is used to trigger github actions to sync branches 
from the llvm-project DoE fork with the upstream repository. 

List of synced branches: 


| Local branch | Upstream branch | Action file                                          | Schedule     | Status |
| ------------ | --------------- | ---------------------------------------------------- | ------------ | ------ |
| master       | master          | [sync_master.yml](.github/workflows/sync_master.yml) | */30 * * * * | ![Matser](https://github.com/llvm-doe-org/sync/workflows/Sync%20master%20branch%20with%20llvm/llvm-project/badge.svg) |
| doe          | master          | [sync_doe.yml](.github/workflows/sync_doe.yml)       | */30 * * * * | ![Doe](https://github.com/llvm-doe-org/sync/workflows/Sync%20doe%20branch%20with%20llvm/llvm-project/badge.svg) |
