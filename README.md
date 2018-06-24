# Panda3d for Astron

This is an old version of panda3d (v1.9.0) designed for astron. This version is specifically used to
work with the leaked toontown-infinite sourcecode. Newer versions of panda3d do not work with the source
and would require extensive work on the source.


## Building

### Linux

Requirements:
`sudo apt-get install build-essential pkg-config python-dev libpng-dev libjpeg-dev libtiff-dev zlib1g-dev libssl-dev libx11-dev libgl1-mesa-dev libxrandr-dev libxxf86dga-dev libxcursor-dev bison flex libfreetype6-dev libvorbis-dev libeigen3-dev libopenal-dev libode-dev libbullet-dev nvidia-cg-toolkit libgtk2.0-dev`

`python2.7 makepanda/makepanda.py --everything --wheel --no-egl --no-gles --no-gles2`