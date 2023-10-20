include_directories(../)

add_executable(testserver testserver.cc)

target_link_libraries(testserver mymuduo pthread)