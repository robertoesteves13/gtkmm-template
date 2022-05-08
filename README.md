# GTKMM Template

This template should be a good starting point to everyone that wants to learn how to build GTK apps using C++.

## Building

Just clone the repository and use the commands to setup and build:

```bash
meson setup builddir
meson compile -C builddir
```

## Motivation

Made this in very little time just to learn if I can replicate the same configuration I made [here](https://github.com/robertoesteves13/gtkmm-cmake). I can say it's way easier and satisfying to use Meson instead of CMake, it feels like everything works as expected. The C++ development experience shouldn't be about spending most of your time to make the build tool just work. 
