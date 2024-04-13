# Version Management

- Version Naming Rule
- x.y.z
> - x => Major 
> - y => Minor
> - z => Patch

## Release Version Flow

_we should follow the flow to release our product_

1. Create a new branch vx.x.x, e.g. v2.0.0
2. Modify file_version_info.txt

> - filevers
> - prodvers
> - FileVersion
> - ProductVersion

3. Modify the version of version API
4. git commit, message would be "Version x.x.x"
5. git tag the commit, e.g. git tag v2.0.0
6. git push the branch from local to remote
7. Create release note


## Minor Version

- We only release the version with major feature
- need to merge it to main branch

## Minor Version

- We only release the version 
> - when we need merge dev branch with the version's branch
> - path version is bigger than 5

## Path Version

- We use the version on bug fix on the new version