RetroArch v1.7.5 Build for PocketChip
=====================================

This builds correctly on stable pocketchip firmware (b126)

# WIP Instructions

```
sudo apt update
sudo apt install -y libsdl1.2-dev libsdl2-dev libboost-system-dev libboost-filesystem-dev libboost-date-time-dev libfreeimage-dev libfreetype6-dev libeigen3-dev libcurl4-openssl-dev libasound2-dev libgl1-mesa-dev cmake build-essential pkg-config
```

```
./configure --prefix=/home/chip/retroarch --enable-opengles --disable-oss --disable-sdl --disable-ffmpeg --disable-vg --disable-cg --enable-neon --enable-floathard --disable-wayland --disable-pulse --enable-dylib --enable-hid --enable-zlib --enable-7zip
```

```
make && make install
```

```
cd ~ && ./retroarch/bin/retroarch
```

RetroArch will look odd at first, you will need to download the assets, info, etc inside it and restart it.
