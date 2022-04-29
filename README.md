# Useful scripts
## Find a file
```sh
#!/bin/sh

find / -name "*hede*"
```
#####

## Search for a string
```sh
#!/bin/sh

grep -r "hede" *
```
#####

## Find and delete files
```sh
#!/bin/sh

find . -name ".DS_Store*" |  xargs rm -rf

```
#####
