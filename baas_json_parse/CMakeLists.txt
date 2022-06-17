# CMakeList.txt : CMake project for baas_json_parse, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

# Add source to this project's executable.
add_executable (baas_json_parse "baas_json_parse.cpp" "baas_json_parse.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET baas_json_parse PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
