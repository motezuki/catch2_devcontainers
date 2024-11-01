# TDD with Catch2 v3 and devcontainers

Catch2 v2 is a unit testing framework for C++ applications, it also provides basic micro-benchmarking features and simple BDD macros.
It integrates with cmake building tool and ctest.
In Catch2 V3 changed the approach to use static libraries and multiple headers

**C++14 is the minimum required C++ version**

## Development environment

The development uses a container pre-compiled with c++ development tools and VCpakg
 `mcr.microsoft.com/devcontainers/cpp:1-debian-12`

The CMake building tool is installed from source 
`REINSTALL_CMAKE_VERSION_FROM_SOURCE="3.22.2"`
