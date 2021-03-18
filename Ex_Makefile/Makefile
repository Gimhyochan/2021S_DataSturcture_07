target = main
src = main.o a.o b.o

$(target) : $(src)
	g++ -o $@ $^

%.o : %.cpp
	g++ -c -o $@ $^

clean:
	rm $(target) $(src)