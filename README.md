Beruben Interpreter
===================

An interpreter for the Beruben language.
See docs/beruben_specification.md for details on syntax.

License: LGPL 2.1 or later

Written by rubenwardy.

Building
========

Windows builds will be provided at a later date.

Linux
-----

```
sudo apt-get install build-essential
cmake .
make -j3

# install
sudo make install
beruben examples/hello_world.br -s

# or portable
./bin/beruben examples/hello_world.br -s
```

