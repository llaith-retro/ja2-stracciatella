CMAKE_MINIMUM_REQUIRED(VERSION 3.1)

PROJECT(lua)

FILE(GLOB LUA_SRC lua/src/*.c)

ADD_LIBRARY(lua ${LUA_SRC})
