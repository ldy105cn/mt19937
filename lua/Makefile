# use your path
SKYNET = ../../../
TARGET = $(SKYNET)luaclib/mt19937.so

$(TARGET) : ../c/mt19937-64.c lua-mt19937.c
	gcc -Wall -g --shared -fPIC -o $@ $^ -I../c -I$(SKYNET)3rd/lua
