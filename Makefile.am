AUTOMAKE_OPTIONS = subdir-objects
ACLOCAL_AMFLAGS = ${ACLOCAL_FLAGS}

lib_LTLIBRARIES = utp/libutp.la
utp_libutp_la_SOURCES = utp.cpp utp_utils.cpp
utp_libutp_la_CXXFLAGS = -c -DPOSIX -I . -I utp_config_lib
libutp_includedir=$(includedir)/utp
libutp_include_HEADERS= utp.h utp_utils.h utypes.h
