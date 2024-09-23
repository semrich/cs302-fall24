EXECUTABLES = bin bin/sb-read bin/sb-analyze bin/sb-play 
CPP = g++
CFLAGS = -Wall -Wextra

all: $(EXECUTABLES)

bin:
	mkdir bin

clean:
	rm -f bin/*

bin/sb-read: sb-read.cpp
	$(CPP) -o bin/sb-read sb-read.cpp

bin/sb-analyze: sb-analyze.cpp disjoint-rank.cpp
	$(CPP) $(CFLAGS) $(INCLUDE) -o bin/sb-analyze sb-analyze.cpp disjoint-rank.cpp

bin/sb-play: sb-play.cpp disjoint-rank.cpp
	$(CPP) $(CFLAGS) $(INCLUDE) -o bin/sb-play sb-play.cpp disjoint-rank.cpp
