add_subdirectory(process-cpp-minimal)
add_subdirectory(android-emugl)
add_subdirectory(xdg)

set(BUILD_TESTING OFF)
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-error")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-error")
add_subdirectory(backward-cpp)
add_subdirectory(cpu_features)
