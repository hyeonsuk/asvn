asvn: asvn.o handles.o
	gcc -o asvn -Xlinker --start-group asvn.o handles.o -Xlinker --end-group

asvn.o:	asvn.c
	gcc -c -o asvn.o asvn.c

handles.o: handles.c
	gcc -c -o handles.o handles.c

clean:
	rm -rf *.o asvn
