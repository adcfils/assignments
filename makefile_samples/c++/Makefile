

all: build

build-filediff:
	g++ filediff.cpp -o filediff --std=c++11

build-tunnel:
	g++ tunnel.cpp -o tunnel -Wall

build: build-filediff build-tunnel
    
run-p1:
	./filediff

run-p2:
	./tunnel
	
clean:
	rm -f tunnel filediff *.in *.out
