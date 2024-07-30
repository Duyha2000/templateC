cmake_minimum_required(VERSION 3.15)
project(LearnC C)

set(CMAKE_C_STANDARD 99)

include_directories(${CMAKE_SOURCE_DIR})

add_executable(LearnC Lession01/Thuchanh/BT1.c Lession01/Thuchanh/BT2.c
        "main .c"
        Lession01/Thuchanh/BT3.c
        Lession01/Baitap/BT1.c
        Lession01/Baitap/BT2.c
        Lession01/Baitap/BT3.c
        Lession02/Thuchanh/BT1.c
        Lession02/Thuchanh/BT2.c
        Lession02/Baitap/BT1.c
        Lession02/Baitap/BT2.c
        Lession02/Baitap/BT3.c
        Lession02/Thuchanh/BT3.c
        Lession01/run.c
        Lession02/run.c
        Lession00/run.c
        Lession00/Baitap/BT1.c
        Lession00/Baitap/BT2.c
        Lession00/Baitap/BT3.c
        Lession00/Thuchanh/BT1.c
        Lession00/Thuchanh/BT2.c
        Lession00/Thuchanh/BT3.c)
