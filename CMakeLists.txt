cmake_minimum_required(VERSION 2.8)	
										

project(lab2_info)			

add_library(
	Function 
	STATIC 
	Function.cpp
)	

add_executable(
	AK_Lab2 
	AK_Lab2.cpp
)	

target_link_libraries(AK_Lab2 Function)		

