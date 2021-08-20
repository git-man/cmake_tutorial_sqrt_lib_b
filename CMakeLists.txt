cmake_minimum_required(VERSION 3.20)

# set project name
project(DepB
	VERSION 4.3.2.1
	LANGUAGES CXX
	)

add_library(depb_compiler_flags INTERFACE)
target_compile_features(depb_compiler_flags INTERFACE cxx_std_11)
