# Version Management

## Version Naming Rule

- `x.y.z` Format
  - `x` => Major Version
  - `y` => Minor Version
  - `z` => Patch Version

## Release Version Flow

_Follow this flow to release our product:_

1. Create a new branch named after the version, e.g., `v2.0.0`.
2. Modify `file_version_info.txt`:
   - `filevers`
   - `prodvers`
   - `FileVersion`
   - `ProductVersion`
3. Update the version in the version API.
4. Commit the changes with the message: "Version x.x.x".
5. Tag the commit, e.g., `git tag v2.0.0`.
6. Push the branch from local to remote.
7. Create a release note.

## Major Version

- Release a major version only with significant new features.
- Needs to be merged into the main branch.

## Minor Version

- Release a minor version when:
  - Merging the dev branch with the version's branch.
  - The patch version number exceeds 5.

## Patch Version

- Used for bug fixes on the current version.
