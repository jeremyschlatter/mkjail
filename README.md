# mkjail
This contains a script I wrote (```mkjail```) to create chroot jails on Mac OS
X. It works for me on Mac OS X 10.10.5.

I also include a helper script (```recurse```) which recursively calls ```otool
-L``` to find the shared library dependencies of an executable.
