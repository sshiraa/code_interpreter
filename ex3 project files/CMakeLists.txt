cmake_minimum_required(VERSION 3.15)
project(ex3)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_FLAGS -pthread)
add_executable(ex3 main.cpp commands.h Parser.cpp Parser.h Lexer.h Lexer.cpp commands.h commands.cpp ex1.h ex1.cpp Expression.h Expression.cpp Utils.h VarInfo.cpp VarInfo.h SinletonMutex.cpp SinletonMutex.h)

