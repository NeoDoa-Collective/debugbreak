cmake_minimum_required(VERSION 3.26.4)

project(debugbreak)

add_library(debugbreak INTERFACE)
target_sources(debugbreak PRIVATE
	"debugbreak.h"
)
target_include_directories(debugbreak INTERFACE .)