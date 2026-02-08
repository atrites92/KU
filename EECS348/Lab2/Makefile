#Make file for lab2

CC=g++
CFLAGS = -c

all: prog

prog: main.o isOdd.o isEven.o
	$(CC) main.o isOdd.o isEven.o -o prog

main.o: main.c
	$(CC) $(CFLAGS) main.c

isEven.o: isEven.c
	$(CC) $(CFLAGS) isEven.c

isOdd.o: isOdd.c
	$(CC) $(CFLAGS) isOdd.c

clean:
	rm -rf *.o prog
