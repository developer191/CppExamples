
FLAGS= `pkg-config opencv --cflags --libs`
PROGRAM=test

$(PROGRAM): $(PROGRAM).cpp
	$(CXX) $(PROGRAM).cpp -o $(PROGRAM) $(FLAGS)

all: $(PROGRAM)

clean:
	rm -f $(PROGRAM)

