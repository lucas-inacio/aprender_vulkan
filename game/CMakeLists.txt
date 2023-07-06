add_executable(game src/game.cpp)
target_link_libraries(game glfw glm Vulkan::Vulkan)