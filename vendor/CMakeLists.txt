include(ExternalProject)

externalproject_add(aegis.cpp
  SOURCE_DIR ${CMAKE_CURRENT_SOURCE_DIR}/aegis.cpp/aegis
  BINARY_DIR ${CMAKE_CURRENT_BINARY_DIR}/aegis.cpp.build
  INSTALL_DIR ${CMAKE_CURRENT_BINARY_DIR}/aegis.cpp.install
  CMAKE_ARGS -DCMAKE_BUILD_TYPE=RelWithDebInfo
)
