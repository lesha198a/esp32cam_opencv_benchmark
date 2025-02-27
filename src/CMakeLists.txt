# This file was automatically generated for projects
# without default 'CMakeLists.txt' file.

FILE(GLOB_RECURSE app_sources ${CMAKE_SOURCE_DIR}/src/*.*)

idf_component_register(SRCS ${app_sources})
# create spiffs partition (named 'storage') from the ../spiffs_image directory
#spiffs_create_partition_image(storage ../data FLASH_IN_PROJECT)
