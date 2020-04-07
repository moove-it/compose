### Get stated

The aim of this tool is to help developers using `docker-compose` for that pourpose its enable
a set of default options that can be using on the project.

By default the command that is being executed is `docker-compose up`, this tool is going to use
the files docker-compose.yml and docker-compose.[COMPENV_FILE].override.yml where `COMPENV_FILE`
is obtained from a file on the root of the project `.compenv` (if the file doesn't exist the
default env is going to be dev)

*File: .compenv*
```
COMPENV_FILE=prod
```

This is a example file for the production environment
