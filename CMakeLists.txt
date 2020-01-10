cmake_minimum_required(VERSION 3.3)
project(Lsn14_Example_semaphore2)

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall -Werror")

set(SOURCE_FILES main.c)
add_executable(semaphore2 ${SOURCE_FILES})
target_link_libraries(semaphore2 pthread)
