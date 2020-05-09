# Project Gutenberg Drop Caps

All (or close to all) scanned Drop Caps from Project Gutenberg prior to April 2020, with 99%-match duplicates removed.

See (large|small)-with-labels-n.jpg files for previews and (somewhat messy) filenames. Number in filename references original Gutenberg ID.

# Notes

Preview images generated with imagemagick's montage. Example:

```
montage -label "%t" *.* -tile 32x18 -geometry "160x160+2+2>" -frame 0 -quality 90 large-with-labels.jpg
```
