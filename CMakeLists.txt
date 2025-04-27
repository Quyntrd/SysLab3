cmake_minimum_required(VERSION 3.10)
project(SysLab3)

set(CMAKE_CXX_STANDARD 20)
set(THREADS_PREFER_PTHREAD_FLAG ON)
find_package(Threads REQUIRED)
link_libraries(Threads::Threads)

add_executable(generate_matrix  generate_matrix.cpp)
add_executable(task1 task1.cpp)
add_executable(task2 task2.cpp)
add_executable(task3 task3.cpp)