# import-photos

Deduplicates photos and organizes them by date.

## Use

```
import-photos [-c] [-l limit] [-p parallel] [-t] [-v] -d destroot srcroot1 srcroot2...
```

## DEPENDENCIES:

1. `sha2` to calculate file digests
1. `exif` to get date and time stamp from images
1. `ffmpeg` to get date and time stamp from movies
1. `mdls` (optional, included in macOS) to get date stamp from media

## macOS

```
brew install sha2 exif ffmpeg
```
