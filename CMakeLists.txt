cmake_minimum_required(VERSION 3.0)

project(cmake_modules)

include(GNUInstallDirs)

install(FILES 
    FindCheck.cmake
    FindDependency.cmake
    ProtectTarget.cmake

    DESTINATION ${CMAKE_INSTALL_FULL_DATAROOTDIR}/cmake-3.10/Modules/
    )
