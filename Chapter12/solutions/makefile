# This makefile contains the instructions for compiling all exercises
# Some advanced functions are used, such as definition of the variables, CC, and references $@ and $<.

# C++ compiler
CC=g++

# All programs to be generated
all: program1 program2

program1: exercise1.cc
	$(CC) -o $@ $<

program2: exercise2.cc
	$(CC) -o $@ $<

clean:
	rm -f program1
	rm -f program2