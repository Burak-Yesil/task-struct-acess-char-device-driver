CXX      = gcc
CXX_FILE = $(wildcard *.c)
TARGET   = $(patsubst %.c,%,$(CXX_FILE))
CXXFLAGS = -g -std=c17 -Wall -Werror -pedantic-errors -fmessage-length=0 -I../driver

all:
	$(CXX) $(CXXFLAGS) $(CXX_FILE) -o $(TARGET) -lpthread
clean:
	rm -f $(TARGET) $(TARGET).exe *.o *~ core
