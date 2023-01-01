all: hello_world

CC = gcc
CFLAGS = -Wall #-g -c

# Just compile/link all files in one hit.
hello_world: #demo.c lib.c #${CFLAGS} CFLAGS was next to CC
	${CC} ${CFLAGS} hello_world.cpp -o speedtest  

clean:
	rm -f demo