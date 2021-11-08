cmake_minimum_required(VERSION 3.15)

project(learn-github-actions LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(${PROJECT_NAME} main.cpp)

# link library
#target_link_libraries(cpp_learn
#    PRIVATE libUtil)

# include directories
#target_include_directories( cpp_learn
#    PUBLIC src)
