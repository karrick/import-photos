# import-photos

Deduplicates photos and organizes them by date.

## Use

```
find $srcdir -type f -print0 | xargs -0 -L25 -P4 /path/to/import-photos $dstdir
```

## DEPENDENCIES:

1. `sha2` to calculate file digests
1. `exif` to get date and time stamp from images
1. `ffmpeg` to get date and time stamp from movies

## macOS

```
brew install sha2 exif ffmpeg
```
