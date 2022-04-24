cmake_minimum_required(VERSION 3.22)
project(Mini_Voting_System)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Mini_Voting_System
        ELECTION.H
        MAIN.C)
