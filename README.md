This package provides Haskell bindings to [libudev][libudev], that
allows access to device information. `libudev` is part of [udev][udev]
device manager for linux kernel.

To build library you need to install `libudev-dev` (Debian, Ubuntu) first.

To build [examples](examples) you need to configure package with
`examples` flag. The examples are ported from this [tutorial][tutor].

### Build Status [![Build Status][status-img]][status-link]

### Maintainer <pxqr.sta@gmail.com>

Feel free to report bugs and suggestions via github
[issue tracker][issues] or the mail.

[udev]:        http://cgit.freedesktop.org/systemd/systemd/tree/src/udev
[libudev]:     http://www.freedesktop.org/software/systemd/libudev/
[tutor]:       http://www.signal11.us/oss/udev
[status-img]:  https://travis-ci.org/pxqr/udev.png
[status-link]: https://travis-ci.org/pxqr/udev
[issues]:      https://github.com/pxqr/udev/issues
