# Miscellaneous

## Convert a mediawiki doc to odt  
https://wiki.lpi.org/wiki/DevOps_Tools_Engineer_Objectives_V1  
View Source -> Copy&Paste in text objectives.md  
```
pandoc objectives.md -f mediawiki -t odt -s -o objectives.odt
```
## odt to github markdown  
```
pandoc objectives.odt -f odt -t gfm -s -o objectives.md
```
