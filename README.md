# Novoda Deprecated Libraries Archive

This is the Novoda Deprecated Libraries Archive, where projects that are no longer actively maintained are laid to rest.

### Create a bundle for the archive
To make a git bundle from current project from inside project directory execute: 
`git bundle create [file_name] --tags --branches`

### Resurrect from a bundle

To resurrect/extract compresed bundle and make it to normal folder structure: 
- `mkdir [PROJECT_NAME]` 
- `git init`
- Copy bundle into directory 
- `git pull [file_name] --tags --branches`
