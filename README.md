Flycast
===========
Flycast is a multi-platform Sega Dreamcast emulator.

Disclaimer
==========
All code contritbuted to this fork is *not* bound by the Individual Contributor License Agreement of the upstream repository (https://github.com/reicast/reicast-emulator) and shall *not* be considered as a contribution to the upstream repository.

Compile instructions in Ubuntu for Retroarch (64 bit)
=====================================================
`git clone https://github.com/christianhaitian/flycast.git'
`cd flycast`
`export _opts="CC_AS=cc HAVE_OPENMP=1 FORCE_GLES=1 HAVE_LTCG=0 WITH_DYNAREC=arm64 platform=goadvance ARCH=arm64"` \
`make clean` \
`make -j$(nproc) ${_opts} V=1`
