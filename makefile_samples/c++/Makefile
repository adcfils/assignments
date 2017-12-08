

all: build

build-plants:
	g++ plants.cpp -o plants --std=c++11

build-palace:
	g++ palace.cpp -o palace -Wall

build: build-filediff build-tunnel
    
run-p1:
	./plants

run-p2:
	./palace
	
clean:
	rm -f plants palace *.in *.out
