##
## LINUX barebone makefile for c examples : good for all platforms
##
## Simply run make or make clean
##
## Intend this makefile only as a "batch examples updater" after library modification.
##

Libs     := -lsnap7 

CXX      := g++
CC       := gcc
CXXFLAGS :=-O3
CFLAGS   :=

.PHONY: all clean

all: 
	$(CC) $(CFLAGS) -o client ../client.c $(Libs) 
	$(CC) $(CFLAGS) -o server ../server.c $(Libs) 
	$(CC) $(CFLAGS) -o apartner ../apartner.c $(Libs) 
	$(CC) $(CFLAGS) -o ppartner ../ppartner.c $(Libs) 

clean:
	$(RM) client
	$(RM) server
	$(RM) apartner
	$(RM) ppartner
