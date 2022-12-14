all: speedtest

CC = gcc
CFLAGS = -Wall #-g -c

# Just compile/link all files in one hit.
speedtest: #demo.c lib.c #${CFLAGS} CFLAGS was next to CC
	${CC} ${CFLAGS} speedtest.cpp -o speedtest  

clean:
	rm -f demo