# Makefile for stopfile_example
# Date: 26.03.2023

CXXFLAGS = -g -I$(HOME)/cpp_sources/stopfile -Wall -Wextra -std=c++17

stopfile_example: stopfile_example.cpp stopfile_example.o stopfile.o 
	g++ $(CXXFLAGS) -pthread stopfile.o stopfile_example.cpp -o stopfile_example -lstdc++fs
	
stopfile.o: stopfile.cpp stopfile.hpp
	g++ $(CXXFLAGS) -c stopfile.cpp -o stopfile.o
	
