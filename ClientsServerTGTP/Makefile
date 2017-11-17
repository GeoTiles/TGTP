CC     = g++

.PHONY: clean all

all: client

clean:
	rm -rf client *~

client: client.cpp handshake.hpp
	${CC} -o $@ client.cpp	
