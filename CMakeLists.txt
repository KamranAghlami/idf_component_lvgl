file(GLOB_RECURSE SOURCES "src/lvgl/src/*.c")

idf_component_register(SRCS "${SOURCES}" INCLUDE_DIRS "src" PRIV_INCLUDE_DIRS "${CMAKE_SOURCE_DIR}/main/src")
