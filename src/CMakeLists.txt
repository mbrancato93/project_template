cmake_minimum_required (VERSION 2.8.11)
project(template_project_src)

file(GLOB all_src
    "./*.c"
)

add_executable(main ${all_src})
add_library(lmain STATIC ${all_src})
target_link_libraries(main ${LIBS})