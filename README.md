# GTKmm Template

This template should be a good starting point to everyone that wants to learn how to build GTK apps using C++.

## Requirements

This setup requires that you have some things installed on your system, such as:
- Meson build system
- GTKmm 4
- GLibmm
- pkg-config

For that, depending on your operating system, you might do the following:

- **Windows:** Look at tools such as [vcpkg](https://github.com/microsoft/vcpkg#getting-started) and [pkg-config-lite](https://sourceforge.net/projects/pkgconfiglite/).
- **Linux:** Install all dependencies using your system's packet manager.
- **MacOS:** Don't have a clue :(

## Building

Just clone the repository and use the commands to setup and build:

```bash
meson setup builddir
meson compile -C builddir
```

## Contribute

I appreciate any contribution to make this template easier to setup. I'm still learning this vast world called C++ and curious to learn more.
