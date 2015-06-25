all: 


	g++ -g -c -fPIC LN_Class.cpp -o LN_Class.o -I../first
	g++ -shared -L../first -lLongNumber -o libLN_Class.so LN_Class.o
	g++ -g -c main.cpp -I../first 
	g++  main.o -L. -lLN_Class -L../first -I../first -lLongNumber -o TCHMK-2



