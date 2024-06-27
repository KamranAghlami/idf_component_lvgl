file(GLOB_RECURSE SOURCES "src/lvgl/src/*.c")

idf_component_register(SRCS ${SOURCES} INCLUDE_DIRS "${CMAKE_SOURCE_DIR}/components/board/include" "src" REQUIRES esp_timer)
