all: TCPEchoServer4 TCPEchoClient4
	
TCPEchoServer4 : TCPEchoServer4.c DieWithMessage.c TCPServerUtility.c AddressUtility.c
	gcc -g -Wall -o $@ $^ -std=gnu99

TCPEchoClient4 : TCPEchoClient4.c DieWithMessage.c TCPServerUtility.c AddressUtility.c
	gcc -g -Wall -o $@ $^ -std=gnu99

clean:
	rm TCPEchoServer4 TCPEchoClient4

