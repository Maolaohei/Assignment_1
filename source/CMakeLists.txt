# CMakeLists.txt from SILENT HILL 3 Redux by Palm Studios
# Copyright 2016-2018 Alexander Hirsch and Jesse Buhagiar

find_package(GLEW REQUIRED)
find_package(GLU REQUIRED)
find_package(GLUT REQUIRED)

include_directories("../include")
include_directories(SYSTEM "${GLEW_INCLUDE_DIRS}")
include_directories(SYSTEM "${GLUT_INCLUDE_DIR}")
include_directories(SYSTEM "${OPENGL_INCLUDE_DIR}")

add_executable("${CMAKE_PROJECT_NAME}"

    "euclidean1/main.cpp"



)

