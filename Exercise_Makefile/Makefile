CC=g++
OBJS=main.o a.o b.o
TARGET=main.out

.PHONY : clean

all: $(OBJS)
	$(CC) -o $(TARGET) $^
%.o : %.cpp
	$(CC) -c -o $@ $^

clean:
	rm $(TARGET) $(OBJS)
