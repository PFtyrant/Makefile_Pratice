#<target>:<prerequsite> 
#	receipe

# food -> omelet.o -> omelet.c -> gcc -c omelet.c

food: omelet.o main.o
	gcc -o food main.o omelet.o

main.o: main.c
	gcc -c main.c

omelet.o: omelet.c
	gcc -c omelet.c

clean:
	rm -rf food
	rm -rf *.o