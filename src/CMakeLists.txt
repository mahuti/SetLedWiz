add_executable(${PROJECT_NAME} setledwiz.cpp)
target_link_libraries(${PROJECT_NAME} usb-1.0)
install(TARGETS setledwiz DESTINATION bin)