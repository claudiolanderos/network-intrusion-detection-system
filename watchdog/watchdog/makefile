all: watchdog.cpp 
	clang++ -std=c++11 -stdlib=libc++ -Weverything -g -Wall -o watchdog watchdog.cpp -L/usr/lib -lpcap

clean: 
	$(RM) watchdog