
CC=gcc
MODCFLAGS=-Wall

all:		turb_simu

clean:	
	rm -f core *.o turb_simu

ublox_conf:	ublox_conf.c Makefile
	$(CC) $(MODCFLAGS) turb_simu.c -o turb_simu

