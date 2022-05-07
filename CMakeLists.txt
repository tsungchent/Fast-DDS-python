set(SWIG_ROOT_DIR ${CMAKE_CURRENT_SOURCE_DIR}/swig)
set(CMAKE_PROGRAM_PATH "${CMAKE_PROGRAM_PATH};${SWIG_ROOT_DIR}")
add_subdirectory(fastdds_python)
add_subdirectory(fastdds_python_examples)