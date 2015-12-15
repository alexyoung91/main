CXXFLAGS = -std=c++11 -g -ggdb -Wall -Wextra -pedantic -m64
PROGRAM = main

all: $(PROGRAM)

$(PROGRAM): main.o
	$(CC) $(CXXFLAGS) -o $@ main.o

main.o: main.cpp
	$(CC) $(CXXFLAGS) -c main.cpp

clean:
	rm -rf *.o main

.PHONY: all clean
