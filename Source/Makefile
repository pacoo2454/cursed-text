CXX = g++
CXXFLAGS = -Wall
LDFLAGS =
SRC = $(wildcard *.cpp)
OBJ = $(SRC:.cpp=.o)

cursed-text: $(OBJ)
	$(CXX) -o $@.out $^ $(LDFLAGS)

.PHONY: clean
clean:
	rm -rf $(OBJ) cursed-text.out
