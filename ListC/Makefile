#Makefile
#Makefile for assignment 7

EXECUTABLE = list
SOURCE = list.c
CC = gcc
CFLAGS = -Wall -g -std=c99
HEADERS = valgrind 

all: ${EXECUTABLE}

${EXECUTABLE}:
	${CC} ${CFLAGS} ${SOURCE} -o ${EXECUTABLE}

clean:
	rm -f *.o

spotless: clean
	rm -f ${EXECUTABLE}

test: ${EXECUTABLE}
	${HEADERS} ./${EXECUTABLE}

.PHONY: clean spotless test




