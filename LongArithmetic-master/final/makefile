all:
	swig -c++ -python -o LN_Class_wrap.cpp LN_Class.i
	g++ -c -fPIC LN_Class.cpp -o LN_Class.o
	g++ -c -fPIC LongNumber.c -o LongNumber.o
	g++ -fPIC -c LN_Class_wrap.cpp -I/usr/include/python2.7
	g++ -shared LN_Class.o LongNumber.o LN_Class_wrap.o -o _LN_Class.so
