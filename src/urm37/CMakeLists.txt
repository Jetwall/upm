upm_mixed_module_init (NAME urm37
    DESCRIPTION "Ultrasonic Range Finder"
    C_HDR urm37.h
    C_SRC urm37.c
    CPP_HDR urm37.hpp
    CPP_SRC urm37.cxx
    IFACE_HDR iDistance.hpp
    FTI_SRC urm37_fti.c
    CPP_WRAPS_C
    REQUIRES mraa utilities-c)
