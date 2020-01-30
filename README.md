# import-photos

Deduplicates photos and organizes them by date.

## Use

```
import-photos [-c] [-l limit] [-p parallel] [-t] [-v] -d destroot srcroot1 srcroot2...
```

## DEPENDENCIES:

1. `exiftime` from the `exittags` package to get date and time stamp from pictures
1. `ffmpeg` to get date and time stamp from video files
1. `gif2png` (optional) to convert GIF to PNG files
1. `mdls` (optional, included in macOS) to get date stamp from media
1. `openssl` to calculate file digests

## debian / ubuntu

```
sudo apt get exiftime ffmpeg gif2png openssl
```

## macOS

```
brew install exiftime ffmpeg gif2png openssl
```

## RHEL / CentOS

```
sudo yum install exiftime ffmpeg gif2png openssl
```
