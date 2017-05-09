cmake_minimum_required(VERSION 3.7)
project(Manage_Buffer)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        buf_manager_statistic.c
        buf_manager_statistic.h
        dbHandler.c
        dbHandler.h
        define.h
        DemoTest2_1.c
        DemoTest2_2.c
        help_test.h
        manage_buff.c
        manage_buff.h
        manage_strg.c
        manage_strg.h)

add_executable(Manage_Buffer ${SOURCE_FILES})