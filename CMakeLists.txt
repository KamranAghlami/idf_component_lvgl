file(GLOB_RECURSE SOURCES "src/lvgl/src/*.c")

idf_component_register(SRCS ${SOURCES} INCLUDE_DIRS "include" "src")
