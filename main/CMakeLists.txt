file(GLOB_RECURSE SOURCES *.c)
set(MAIN_SRC_DIR ${CMAKE_CURRENT_LIST_DIR})

idf_component_register(SRCS ${SOURCES}
                    INCLUDE_DIRS ${MAIN_SRC_DIR})
