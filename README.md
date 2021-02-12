# mediaelch-dep

Temporary repository that contains binary dependencies.

MediaElch builds its Windows Binaries using MXE.
However, MXE does not provide `opengl32sw.dll`, yet.
This repository exists for the sole purpose of providing this dependency.

In the future, this dependency will either be build by MXE or will
be downloaded from another source as Git is _not_ intended for binary files.

The DLL originates from Qt 5.15.2. This is also recommended by <https://wiki.qt.io/Cross_compiling_Mesa_for_Windows>
