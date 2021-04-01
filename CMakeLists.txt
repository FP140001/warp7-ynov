cmake_minimum_required(VERSION 3.10)
project (Thermo)
add_executable(Thermo Thermo.c)
install(TARGETS Thermo RUNTIME DESTINATION /usr/bin)
