makefile:

all: recursive

clean: 
	~rm recursivesample.o recursive.exe recursive
	
recursive: recursivesample.o
	g++ -g -o recursive recursivesample.o
	
recursivesample.o: recursivesample.cpp
	g++ -c -g recursivesample.cpp
