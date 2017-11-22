

all: build

build-filediff:
	g++ filediff.cpp -o filediff --std=c++11

build-tunnel:
	g++ tunnel.cpp -o tunnel -Wall

build: build-filediff build-tunnel
    
run-p1:
	./tunnel

run-p2:
	./filediff
	
clean:
	rm -f tunnel filediff *.in *.out
