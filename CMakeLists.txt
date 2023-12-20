cmake_minimum_required(VERSION 3.20.0)

set(BOARD stm32f769i_disco)
find_package(Zephyr)
project(stm32f769i_playground)


target_sources(app PRIVATE src/main.cpp)
