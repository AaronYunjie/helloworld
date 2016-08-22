objects = printhello.o hello.o

sayhello : $(objects)
	cc -o sayhello $(objects)

printhello.o : printhello.c
hello.o : hello.c

.PHONY : clean
clean :
	rm sayhello $(objects)
