CC=g++
CFLAGS=-Wall -g
COFLAGS=-Wall -c -g

all: gpsPlus

gpsPlus: gpsDemo.o gga.o
	$(CC) $(CFLAGS) gga.o gpsDemo.o -o gpsPlus

gpsDemo.o: gpsDemo.cpp
	$(CC) $(COFLAGS) gpsDemo.cpp

gga.o: gga.cpp
	$(CC) $(COFLAGS) gga.cpp

clean:
	rm plusGPS *.o
