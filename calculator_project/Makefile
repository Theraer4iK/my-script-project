CC = g++
CFLAGS = -Wall -c
LDFLAGS =

all: main

main: main.o calculator.o
	$(CC) $(LDFLAGS) main.o calculator.o main

main.o: main.cpp calculator.h
	$(CC) $(CFLAGS) main.cpp

calculator.o: calculator.cpp calculator.h
	$(CC) $(CFLAGS) calculator.cpp

clean:
	rm -f *.o main
