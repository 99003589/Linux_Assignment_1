all: server client

server: server.c 
	gcc -o server.out server.c -lrt
	
client: client.c 
	gcc -o client.out client.c -lrt
	
runclient:
	./client.out

runserver:
	./server.out

clean:
	rm -rf *.out *.o
