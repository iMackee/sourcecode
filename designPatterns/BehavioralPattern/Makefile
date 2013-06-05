#----------------------
# To be changed
#----------------------
BIN = AbstractFactory

SOURCE := \
	Product.cpp \
	Product.h \
	AbstractFactory.cpp \
	AbstractFactory.h \
	main.cpp

PATTERN = ???
SOURCE_PATTERN = $(PATTERN).cpp
#----------------------
# Do not change
#----------------------
CC = g++

all: $(BIN) $(PATTERN)

$(BIN): $(SOURCE)
	$(CC) $(SOURCE) -o $(BIN)

$(PATTERN): $(SOURCE_PATTERN)
	$(CC) $(SOURCE_PATTERN) -o $(PATTERN)

clean:
	rm -f $(BIN) $(PATTERN)

#----------------------
