bin/parser: expr.c interp.c main.c scan.c tree.c bin
	cc -o bin/parser -g expr.c interp.c main.c scan.c tree.c

bin: 
	mkdir bin

clean:
	rm -rf bin *.o

test: bin/parser
	bin/parser input01
	bin/parser input02
	bin/parser input03 || echo 
	bin/parser input04 || echo 
	bin/parser input05 || echo
