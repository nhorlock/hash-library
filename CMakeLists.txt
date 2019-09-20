add_library(hash-lib sha256.cpp)
target_include_directories(hash-lib PUBLIC ${CMAKE_CURRENT_LIST_DIR})