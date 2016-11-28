cmake_minimum_required (VERSION 2.8.11)
project (HELLO)

add_executable (hello hello.c)
install (TARGETS hello DESTINATION bin)
