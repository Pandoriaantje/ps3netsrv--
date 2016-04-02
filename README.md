ps3netsrv--
===========

C++ implementation of the ps3netsrv server

Supported platforms:
- Mac
- Linux
- FreeBSD 10

Build the source:
```
git clone --recursive https://github.com/Pandoriaantje/ps3netsrv--.git
git submodule update --init
make
```

If you prefer to use gcc:
```
make CXX=g++
```

Run the server:
```
ps3netsrv++ /path/to/serve
```
