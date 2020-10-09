CFLAGS = -g -Wall -I /root/build/release-install-cpp11/include 
LIBS = -L /root/build/release-install-cpp11/lib -lmuduo_base -lmuduo_net -lpthread
SRCS = socks4a.cc
OBJS = $(SRCS:.cc=.o)
EXECUTABLE = socks4aMain
CC = g++

all:
	$(CC) $(CFLAGS) -o $(EXECUTABLE) $(SRCS) $(LIBS) -std=c++11

.PHONY:clean
clean:
	rm $(EXECUTABLE) $(OBJS)
