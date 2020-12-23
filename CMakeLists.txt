cmake_minimum_required(VERSION "3.19.1")

project("Prova")

file(GLOB SRCFILES
	*.cpp
	*.h)

add_executable("${PROJECT_NAME}" ${SRCFILES})
