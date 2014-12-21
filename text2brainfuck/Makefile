CC = gcc
CFLAGS = -O3 -Wall

%.c: txt2bf

all: clean txt2bf

txt2bf: txt2bf.o

txt2bf-debug: txt2bf.c
	$(CC) $(CFLAGS) -g -o txt2bf-debug txt2bf.c

clean:
	rm -f *.o txt2bf
