objects = hello.o
hello : $(objects)
	cc -o hello $(objects)
hello.o : hello.c
	cc -c hello.c
clean :
	rm hello $(objects)
