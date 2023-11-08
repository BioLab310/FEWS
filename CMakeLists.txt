cmake_minimum_required(VERSION 3.17)
project(FEWS_Counter)

set(CMAKE_CXX_STANDARD 11)

add_executable(FEWS_Counter
        Basic.cpp
        Basic.h
        hash.cpp
        hash.h
        Main.cpp
        neighbor.cpp
        neighbor.h
        reservoir.cpp
        reservoir.h
        FEWS_Count.h
        FEWS_Count.cpp
        MinIds.cpp
        MinIds.h
        IsClosed.h

        IsClosed.cpp FEWS_Improve.h FEWS_Improve.cpp FEWS_FullyDynamic.h FEWS_FullyDynamic.cpp)