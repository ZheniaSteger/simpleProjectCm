cmake_minimum_required(VERSION 2.8)

add_compile_options(-Wall -Wextra -Wpedantic )

add_executable(foo simpleProjectCm.cpp)
target_compile_definitions(intro PRIVATE cxx_lambda_init_captures)