objects = printhello.o hello.o
sayhello : $(objects)
	cc -o sayhello $(objects)
printhello.o : printhello.c
	cc -c printhello.c
hello.o : hello.c
	cc -c hello.c
clean :
	rm sayhello $(objects)
