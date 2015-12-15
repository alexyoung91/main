CFLAGS = -fdiagnostics-color=always -std=gnu99 -g -ggdb -Wall -Wextra -pedantic -m64
PROGRAM = main

all: $(PROGRAM)

$(PROGRAM): main.o
	$(CC) $(CFLAGS) -o $@ main.o

main.o: main.c
	$(CC) $(CFLAGS) -c main.c

clean:
	rm -rf *.o main

.PHONY: all clean
