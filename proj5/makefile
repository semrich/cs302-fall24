CXX=		g++
CXXFLAGS=	-g -Wall -std=gnu++11
SHELL=		bash
PROGRAMS=	worddice

all:            worddice

worddice: worddice.cpp
	$(CXX) $(CXXFLAGS) -o $@ $^

clean:
	rm -f $(PROGRAMS)