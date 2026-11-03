cmake_minimum_required(VERSION 4.0.0)

find_package(Zephyr REQUIRED HINTS $ENV{ZEPHYR_BASE})
project(rl-cher-taunt)

target_sources(app PRIVATE src/main.c)
