# LIBMILL [![Build Status](https://travis-ci.org/sustrik/libmill.svg?branch=master)](https://travis-ci.org/sustrik/libmill)

Libmill is a library that introduces Go-style concurrency to C.

## Documentation

For the documentation check the project website:

http://libmill.org

## Setup

```sh
$ ./autogen.sh
$ ./configure
$ make
$ make check
$ sudo make install
```

for debug:

```sh
$ ./configure --disable-shared --enable-debug --enable-valgrind
```

## License

Libmill is licensed under MIT/X11 license.
