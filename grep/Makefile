
vpath %.c src
vpath %.h include

PROGRAM = grep

$(PROGRAM): grep.o

grep.o: grep.c


.PHONY: clean
clean:
	rm -rf *.o $(PROGRAM)
