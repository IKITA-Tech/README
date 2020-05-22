# README
Welcome to IKITA's GitHub. Before you start to create or to commit to the repositories, please follow the guidelines below to make our code party sustainable. 

## Create a repository
- The words in the repository name are seperated by a dash `-`. The name should be comprehensive but sufficient descriptive. For example, `data-backend-service` is good. `backend-service` is too general and `write-pose-data-service` is not all-inclusive.
- Always choose private repository first. We can make it open when we are sure.
- You don't have to initialize the repository with a README or .gitignore, but you must have them (and maintain them) at the root folder.
- A licence is not needed at this stage.

## Create a branch
- Use `master` exclusively as the production branch.
- Always create a branch `develop`. This is the development branch.
- Branch your feature branches from `develop`.

## Merge a branch
- Merge feature branches to `develop` with at least one pull request approval.
- Merge `develop` to `master` for a release.
- Delete the feature branch after merging.
