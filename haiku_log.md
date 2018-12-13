# 源码目录分析


This document is supposed to give you some insight where you'll find what in the source repository tree. If you're familiar with Haiku already, you will notice that the tree layout to some degree mirrors the structure a Haiku installation has on disk.

Things that are built are usually put under "src", for example, there is a "data", and a "src/data" folder - the former for example contains scripts or settings ready to be copied to the Haiku image, while the latter for example contains the MIME types database that first have to be converted from a format that is easy to edit to what Haiku expects.

- src all files that have to be built
    - add-ons everything you'll find in /boot/system/add-ons/ including all kernel drivers, media codecs, and Translators etc.
    - apps the GUI applications that are not preferences apps
    - bin command line applications such as the GNU tools
    - build files to allow using the Haiku build-tools on non-BeOS compatible platforms
    - data data files of any kind like the MIME type database or keymap files
    - kits the public API of Haiku that is organized in kits - except the "kernel kit" which is part of libroot.so
    - libs static and shared libraries that are used by Haiku applications
    - preferences the preferences applications
    - servers
    - system most of the files you'll find in the /boot/system directory - they make up the core of Haiku without the public userlevel API besides everything what is in libroot.so
        - boot The boot loader with all supported platforms
        - glue The glue code that makes shared libraries execute their global constructors/destructors, and executables call main().
        - kernel The kernel and all of its core services and supported architectures
        - ldscripts linker scripts for building various parts of Haiku
        - libroot Everything that is exported by libroot.so which is the POSIX API and the kernel kit
        - runtime_loader the userland ELF loader that loads and starts executables
    - tests this more or less mirrors the tree itself, and contains test applications for the various subsystems (like an app_server that runs as a window under BeOS), some of them are to be used in a C++ unit test suite.
    - tools Tools that are either needed to build Haiku or are in other ways useful even when not running under Haiku
- headers all shared private and public headers
    - build
    - compatibility header files that increase the compatibility of Haiku to other systems; currently, you'll find some headers that allow compilation of some BSD tools (for libbsd.so).
    - cpp
    - glibc
    - gnu
    - legacy non-POSIX headers that are still needed by some ancient or not so well maintained tools
    - libs
    - os the public headers that define the Haiku API
    - posix the POSIX API as supported by Haiku
    - private private headers that are shared throughout Haiku components
    - tools
Now that the basic idea should be clear, let me point out some inconsistencies in the current layout that haven't been resolved yet:

- Top-level "docs" contains doxygen source files that will have to be built; the whole directory layout there is a bit untidy, anyway.
- Some of the tools in "src/tools" will also be part of a Haiku installation, and also, some of the binaries in "src/bin" are needed to build Haiku (such as mimeset)
- "src/system/ldscripts" don't really belong where they are; they should be in "build".

see (https://www.haiku-os.org/documents/dev/a_brief_introduction_to_our_source_repository_layout)





