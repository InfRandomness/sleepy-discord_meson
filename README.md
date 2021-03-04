# Sleepy-discord meson template

repository is a little template to get you started on using meson (ninja) to compile your c++ discord bot against [sleepy_discord](https://github.com/yourWaifu/sleepy-discord)

## Instructions :

[Install meson](https://mesonbuild.com/SimpleStart.html#installing-meson)\
[Install ninja](https://github.com/ninja-build/ninja/wiki/Pre-built-Ninja-packages)\
[Install cmake](https://cmake.org/download/)\
Get that repo to your computer and cd into it\
Run `meson subprojects download`\
Run `meson setup builddir`\
Run `ninja -C builddir` (to test if everything is compiling fine)\
Try to launch the binary (should be in the ./build/ directory from the meson.build)
