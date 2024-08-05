CC=gcc
CFLAGS=-O3 -std=c99 -w -lm
TARGET=kmstats26
all: $(TARGET)

$(TARGET): kmstats26.c
	$(CC) kmstats26.c $(CFLAGS) -o $(TARGET)

clean:
	$(RM) $(TARGET)
