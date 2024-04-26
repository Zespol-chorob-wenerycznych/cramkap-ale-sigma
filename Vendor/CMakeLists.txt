add_subdirectory(${CMAKE_CURRENT_SOURCE_DIR}/glfw)
add_subdirectory(${CMAKE_CURRENT_SOURCE_DIR}/glad-4.6-cmake)

target_link_libraries(${PROJECT_NAME} PRIVATE
    glfw
    glad
)