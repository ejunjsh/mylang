bin: 
	mkdir bin

bin/scanner: main.c scan.c bin
	cc -o bin/scanner -g main.c scan.c

clean:
	rm -rf bin *.o

test: bin/scanner
	bin/scanner input01
	bin/scanner input02
	bin/scanner input03
	bin/scanner input04 || echo 
	bin/scanner input05 || echo