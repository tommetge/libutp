AUTOMAKE_OPTIONS = subdir-objects
ACLOCAL_AMFLAGS = ${ACLOCAL_FLAGS}

lib_LTLIBRARIES = libutp-0.1.la
libutp_0_1_la_SOURCES = utp.cpp utp_utils.cpp
libutp_0_1_la_CXXFLAGS = -c -DPOSIX -I . -I utp_config_lib
libutp_includedir=$(includedir)/libutp
libutp_include_HEADERS= utp.h utp_utils.h utypes.h
