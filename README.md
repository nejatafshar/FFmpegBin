# FFmpegBin

FFmpeg light builds for different platforms. Only frequently used formats and codecs are enbled and is optimized for size. SSL support is included in all platforms.

## Platforms

- Windows 32 and 64 (VS)
- Linux 64 (gcc)
- macOS
- Android (armeabi, armeabi-v7a, arm64-v8a, x86)
- iOS

Build files for each platform are placed in separate branches.

## Usage
To get only a specific branch run `git clone` by passing the branch name to `-b` argument with `--single-branch` option:
    git clone -b linux --single-branch https://github.com/nejatafshar/FFmpegBin.git
