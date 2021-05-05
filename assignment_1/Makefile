all: average main
average:
	gcc -std=c99 average.c -c
main:
	gcc average.o main.c -o average
clean:
	&(RM) *.o
