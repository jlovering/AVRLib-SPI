cmake_minimum_required(VERSION 3.23)

project (AVRLib-SPI VERSION 1.0)

add_avr_library(AVRLib-SPI
    source/spi.c)

avr_target_include_directories(AVRLib-SPI 
    PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/include)