cmake_minimum_required(VERSION 3.27.0)
project("MySkillboxApp" VERSION 0.1.0)

set(CMAKE_CXX_STANDARD 14)



add_executable(MySkillboxApp main.cpp)

set(CMAKE_PREFIX_PATH "C:/Qt/5.15.2/mingw81_64/lib/cmake")

find_package(Qt5 COMPONENTS

        Core

        Gui

        Widgets

        REQUIRED)

target_link_libraries(MySkillboxApp

        Qt5::Core

        Qt5::Gui

        Qt5::Widgets)

