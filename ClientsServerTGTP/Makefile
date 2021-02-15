#http://geanydbg.sourceforge.net/walkthrough.htm

# Makefile para os programas dos apontamentos
CC     = g++

.PHONY: clean all

all: client

clean:
	rm -rf client

client: client.cpp handshake.hpp
	${CC} -o $@ client.cpp	
