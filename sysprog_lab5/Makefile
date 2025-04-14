CC=gcc
CFLAGS=-Wall -Wextra

all: guess_number_signals guess_number_fifo

guess_number_signals: guess_number_signals.c
	$(CC) $(CFLAGS) -o $@ $<

guess_number_fifo: guess_number_fifo.c
	$(CC) $(CFLAGS) -o $@ $<

clean:
	rm -f guess_number_signals guess_number_fifo

.PHONY: all clean
