# Useful scripts
## Find a file
```sh
find / -name "*hede*"
```
#####

## Search for a string
```sh
grep -r "hede" *
```
#####

## Find and delete files
```sh
#!/bin/sh

find . -name ".DS_Store*" |  xargs rm -rf

```
#####
