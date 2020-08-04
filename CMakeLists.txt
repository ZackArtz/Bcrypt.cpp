cmake_minimum_required(VERSION 3.5)
project(bcryptcpp)

include_directories(include)

add_library(${PROJECT_NAME} src/bcrypt.cpp src/blowfish.cpp src/blf.h src/openbsd.h include/bcrypt.h)