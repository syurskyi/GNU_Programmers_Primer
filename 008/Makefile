CC = c++
CPPFLAGS = -g -Wall -I../Headers
LDFFLAGS = -L../lib/ -lera

all: main.run

main.run: main.cpp
	$(CC) main.cpp $(LDFFLAGS) -o main.run
main.o:
	$(CC) $(CPPFLAGS) -c main.cpp
clean:
	rm -f *.o
	rm -f.run