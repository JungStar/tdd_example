add_library(helper INTERFACE)
target_include_directories(helper INTERFACE include)

add_subdirectory(tests)