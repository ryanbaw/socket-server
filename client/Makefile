all: client
	
client : client.c DieWithMessage.c TCPServerUtility.c AddressUtility.c
	gcc -g -Wall -o $@ $^ -std=gnu99

clean:
	rm client

