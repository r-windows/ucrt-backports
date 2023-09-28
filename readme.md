# ucrt-backports

Libraries built with gcc 10 on ucrt64.

Notes:
 - Only needed for some C++ libs which use parts of the standard library that changed in g++ 11.
 - Remove `${MINGW_PACKAGE_PREFIX}-cc` from PKGBUILD to prevent upgrading the preinstalled gcc 10.
 - The preinstalled toolchain only has static pthreads so building shared libs may not work.
