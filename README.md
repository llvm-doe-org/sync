# Sync branches from DoE llvm-project fork

This repository is used to trigger github actions to sync branches 
from the llvm-project DoE fork with the upstream repository. 

List of synced branches: 


| Local branch | Upstream branch | Action file                                          | Schedule     | 
| ------------ | --------------- | ---------------------------------------------------- | ------------ |
| master       | master          | [sync_master.yml](.github/workflows/sync_master.yml) | */30 * * * * |
| doe          | master          | [sync_doe.yml](.github/workflows/sync_doe.yml)       | */30 * * * * |
