# Example

```bash
$ svn2git --help
```

```
Usage: svn2git [options] EXPORT_DIRECTORY

Specific options:
    -r REPOSITORIES_FILE,            Path to file containing repositories to migrate
        --repositories
    -A, --authors AUTHORS_FILE       Path to file containing svn-to-git authors mapping
    -l, --localy                     Run command localy
        --dry-run                    Prints out commands without running them
    -v, --verbose                    Be more verbose. May be given more than once

    -h, --help                       Show this message
```

```bash
$ svn2git -r repositories.yml -A authors.txt
```
