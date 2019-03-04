How to clean dot underbar (._)files in MacOSx
==


A Terminal command on OS X, (attempt to merge & delete the files)

`dot_clean -m /Volumes/Mounted-SMB-share`


Or just delete them via 'find'

`find /Volumes/Mounted-SMB-share -name ._\* -delete`
