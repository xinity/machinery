# Internal Notes

## Making a Release

To make a release, you should do the following:

1. Make sure all changes are documented in the [Release Notes](RELEASENOTES.md).
2. Bump up/adapt the version number that is declared in `cli.tcl`.
3. Make binaries using the script in the `make` sub-directory.
4. Tag the release in git using: `git tag -a -m "Version vX.Y" vX.Y`.
5. Push the tag to the main repository: `git push --tags`.
