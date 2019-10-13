jtc: jtc.cpp $(wildcard ./lib/*.hpp) $(wildcard ./lib/*.h)
	c++ -I./lib -Wall -std=c++14 -Ofast jtc.cpp -o jtc

install: jtc
	cp jtc /usr/local/bin
	chmod +x /usr/local/bin/jtc

