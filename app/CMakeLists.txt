cmake_minimum_required(VERSION 3.13.1)
set(ZMK_APP_NAME googootkah)
find_package(Zephyr)
project(${ZMK_APP_NAME})

target_sources(app PRIVATE
    keymap/keymap_left.keymap
    keymap/keymap_right.keymap
)
