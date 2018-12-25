cmake_minimum_required(VERSION 3.13)
project(Trip_Organizer C)

set(CMAKE_C_STANDARD 99)
include_directories(include)

add_executable(Trip_Organizer main.c logic/utils/utils.c logic/menu/menu.c logic/functions/functions.c model/list/list.c model/destination/destination.c)