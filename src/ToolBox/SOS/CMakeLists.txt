if(WIN32)
if(NOT DEFINED CLR_CMAKE_PLATFORM_ARCH_ARM64)
    add_subdirectory(Strike)
endif(NOT DEFINED CLR_CMAKE_PLATFORM_ARCH_ARM64)
endif(WIN32)
