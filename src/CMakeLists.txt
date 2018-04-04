file(GLOB_RECURSE SOURCES "miv/*.cpp" "miv/*.c" "miv/*.h")
add_executable(miv ${SOURCES})
target_include_directories(miv PRIVATE ".")
