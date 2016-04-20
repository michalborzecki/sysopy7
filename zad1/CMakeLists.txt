cmake_minimum_required(VERSION 3.4)
project(zad1 C)

set(CMAKE_C_FLAGS "-Wall")

add_executable(host host.c)
add_executable(producer producer.c)
add_executable(consumer consumer.c)
