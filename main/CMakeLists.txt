file(GLOB_RECURSE SOURCES
     "${CMAKE_CURRENT_SOURCE_DIR}/*.c"
     "${CMAKE_CURRENT_SOURCE_DIR}/*.cpp")

idf_component_register(SRCS ${SOURCES}
                       INCLUDE_DIRS ".")

