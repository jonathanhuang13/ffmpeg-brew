# ffmpeg-brew

Build FFMPEG with more support than official Homebrew build. Much of this is borrowed from https://github.com/skyzyx/homebrew-ffmpeg.

## Why use this version?

The official `ffmpeg` from homebrew-core does not support all the demuxers and muxers that might be needed. This version supports everything the core version suports including MPEG-DASH streaming, HTTP Live Streaming, and others. 

View all the enabled settings in `Formula/ffmpeg-jonathan.rb`.

## Installation

Install via URL (you won't receive updates):
```
brew tap jonathanhuang13/ffmpeg
brew install ffmpeg-jonathan
brew link --overwrite ffmpeg-jonathan
```
