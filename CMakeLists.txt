cmake_minimum_required(VERSION 3.0)
project(app_project)
add_executable(myapp Prog.c)
install(TARGETS myapp DESTINATION bin)