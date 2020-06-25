cmake_minimum_required(VERSION 3.2)

# source files
set(SRC_FILES ${SRC_FILES}
    ${CMAKE_CURRENT_SOURCE_DIR}/ClassFactory.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/HdbConfigurationManager.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/HdbConfigurationManagerClass.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/HdbConfigurationManagerStateMachine.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/main.cpp
    PARENT_SCOPE)