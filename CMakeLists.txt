cmake_minimum_required(VERSION 3.27)
project(Projet_AP4A)

set(CMAKE_CXX_STANDARD 17)

add_executable(Projet_AP4A main.cpp
        Server.cpp
        Server.h
        Sensor.cpp
        Sensor.h
        Scheduler.cpp
        Scheduler.h)
