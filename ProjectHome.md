The real Tokyo Cabinet uses C99 and uses POSIX APIs, so:
> - it will not compile with Microsoft's compiler
> - it will not build or run on Windows

Additionally the build process uses teh common autoconf mechanism.

This fork:
> - uses C99 if a C99 compiler is available, and uses C++ if not
> - will build on Windows as well as POSIX
> - uses a scons build and configuration system