uSTL for FeOS - r1
------------------

   http://ustl.sourceforge.net

uSTL is a lightweight not-quite-standard STL implementation (see docs/index.html).
This is a port of uSTL to FeOS. Many things have been removed:

- Streams (ugh)
- Serialization
- math.h using code
- Most of SIMD-using code (TODO: completely remove simd.h)

In order to use this library, copy this folder to your sdk/userlib directory, and add your Makefile's
CONF_USERLIBS and CONF_LIBS like this:

CONF_USERLIBS := ustl
CONF_LIBS := -lustl

Have fun trying to port STL-depending C++ code to uSTL!
