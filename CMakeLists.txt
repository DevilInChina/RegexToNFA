cmake_minimum_required(VERSION 3.15)
project(AutoMachines)

set(CMAKE_CXX_STANDARD 20)

add_executable(RegexToNFA RegexToNFA.cpp)
add_executable(PushdownAutomation PDA.cpp )
add_executable(TurningMachine Turning.cpp)