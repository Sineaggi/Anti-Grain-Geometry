cmake_minimum_required(VERSION 2.8)

project (agg)

# If sdl is not available
# add_subdirectory (extern/SDL)

find_package (SDL)
if (SDL_FOUND)
  include_directories (${SDL_INCLUDE_DIR})
endif ()

find_package (Freetype)
if (FREETYPE_FOUND)
  include_directories (${FREETYPE_INCLUDE_DIRS})
  message ("Including ${FREETYPE_INCLUDE_DIRS}")
endif ()

find_package (EXPAT)
if (EXPAT_FOUND)
  include_directories (${EXPAT_INCLUDE_DIRS})
  message ("Including ${EXPAT_INCLUDE_DIRS}")
endif ()

include_directories (include)
include_directories (include/ctrl)
include_directories (include/platform)
include_directories (include/platform/mac)
include_directories (include/platform/win32)
include_directories (include/util)

include_directories (font_freetype)

if (WIN32)
  include_directories (font_win32_tt)
endif ()

include_directories (gpc)

add_subdirectory (src)

get_property(dirs DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR} PROPERTY INCLUDE_DIRECTORIES)
foreach(dir ${dirs})
  message(STATUS "dir='${dir}'")
endforeach()

add_subdirectory (examples)
