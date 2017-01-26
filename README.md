# PJSUA (for Jibri)

This repository contains a modified version of PJSUA suitable for use
with Jibri.

Changes from upstream:

- Ability to fullscreen SDL windows
- Auto fullscreen remote video window
- Auto exit after a call is ended
- Video quality tweaks

At the time of this writing FFmpeg + x264 are used as the H.264 implementation.


## Building

Dependencies:

```
apt install build-essential libv4l-dev libsdl2-dev libavcodec-dev libavdevice-dev libavfilter-dev libavformat-dev libavresample-dev libavutil-dev libswresample-dev libswscale-dev libasound2-dev
```

Build process:

```
git clone git@bitbucket.org:atlassian-video-engineering/jibri-pjsua.git
cd jibri-pjsua
./configure
make dep
make
```

The binary will be located in `pjsip-apps/bin/`.


## Usage

TODO
