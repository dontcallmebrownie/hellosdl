add_executable(${PROJECT_NAME})

target_sources(${PROJECT_NAME} PRIVATE hello.c)

target_link_libraries(${PROJECT_NAME} PRIVATE vendor)

