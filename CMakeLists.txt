cmake_minimum_required(VERSION 3.12)

project(main.run)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(main.run "src/main.cpp")

add_subdirectory(deps/glfw)

find_package(assimp REQUIRED)


target_include_directories(main.run PRIVATE
  deps/glm 
  deps/glfw/include
  deps/glew/include
  ${ASSIMP_INCLUDE_DIRS}
)

target_link_directories(main.run PRIVATE
  deps/glfw/lib
  deps/glew/lib
)

target_link_libraries(main.run PRIVATE
  glfw
  GLEW
  GL
  assimp
)

