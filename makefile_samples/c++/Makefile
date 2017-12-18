all: build

build-plants:
	g++ plants.cpp -o plants --std=c++11 -O3

build-palace:
	g++ madripoor.cpp -o madripoor -Wall -O3

build: build-filediff build-tunnel
    
run-p1:
	./plants

run-p2:
	./madripoor
	
clean:
	rm -f plants madripoor *.in *.out
