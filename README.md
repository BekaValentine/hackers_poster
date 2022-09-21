# Hackers Poster

This is a scan of a poster for the 1995 movie Hackers.

There are three sizes of the file. A small 1000x1545 PNG, a medium 5000x7727 PNG, and a full size 13176x20361 PNG.
There are also the original scans, which were stitched together to form this complete poster.

The file size of the larger two poster images and of the original scans is too large to upload to Github as a single file, and so they have been broken into 10M chunks.

To reconstruct the full size scan, run the following:

```bash
$ cat $FILE.part.?? > $FILE.png
```

The resulting file `$FILE.png` is now the complete image. Replace `$FILE` with the obvious names.
