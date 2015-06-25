all: 
	gcc -std=gnu99 -c -fPIC LongNumber.c -o LongNumber.o
	gcc -shared -o libLongNumber.so LongNumber.o
	gcc -c main.c
	gcc main.o -L. -lLongNumber -o TCHMK-1


