## `cp`
| Options | Meaning |
|---------|---------|
| `-a, --archive` | Copy the files and directories and all of their attributes, including ownerships and permissions. Normally, copies take on the default attributes of the user performing the copy. |
| `-i, --interactive` | Before overwriting an existing file, prompt the user for confirmation. **If this option is not specified, `cp` will silently overwrite files.** |
| `-r, --recursive` | Recursively copy directories and their contents. This option (or the -a option) is required when copying directories. |
| `-u, --update` | When copying files from one directory to another, only copy files that either don't exist, or are newer than the existing corresponding files, in the destination directory. This is useful when copying large numbers of file as it skips over files that don't need to be copied. |
| `-v, --verbose` | Display informative messages as the copy is performed. |


---
## `mv`
| Options | Meaning |
|---------|---------|
| `-i, --interactive` | Before overwriting an existing file, prompt the user for confirmation. **If this option is not specified, `mv` will silently overwrite files.** |
| `-u, --update` | When moving files from one directory to another, only move files that either don't exist, or are newer than the existing corresponding files in the destination directory. |
| `-v, --verbose` | Display informative messages as the move is performed. |


---
## `rm`
| Options | Meaning |
|---------|---------|
| `-i, --interactive` | Before deleting an existing file, prompt the user for confirmation. **If this option is not specified, `rm` will silently delete files.** |
| `-r, --recursive` | Recursively delete directories. This means that if a directory being deleted has subdirectories, delete them too. To delete a directory, this option must be specified. |
| `-f, --force` | Ignore nonexistent files and do not prompt. This overrides the `--interactive` option. |
| `-v, --verbose` | Display informative messages as the deletion is performed. |
