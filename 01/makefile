CPPFLAGS = -I include
VPATH = src include
vpath main.cc src
vpath main.h include

CC = g++

main: main.cc
	$(CC) -Wall $(CPPFLAGS) $^ -o $@
