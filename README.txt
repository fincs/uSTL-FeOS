uSTL for FeOS - r2a - Based on uSTL v1.6
----------------------------------------

   http://feos.mtheall.com/uSTL-FeOS/
   https://github.com/fincs/uSTL-FeOS/
   http://ustl.sourceforge.net

uSTL is a lightweight not-quite-standard STL implementation (see docs/index.html).
This is a port of uSTL to FeOS. Many things have been removed:

- Streams (ugh)
- Serialization
- math.h using code
- Most of SIMD-using code (TODO: completely remove simd.h)

See docs/index.html for more details.

Have fun trying to port STL-depending C++ code to uSTL!
