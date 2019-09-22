cmake_minimum_required(VERSION 2.8)

add_executable(intro simpleProjectCm.cpp)
target_compile_definitions(intro PRIVATE cxx_lambda_init_captures)