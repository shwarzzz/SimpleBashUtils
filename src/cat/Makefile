CFLAGS = -Wall -Werror -Wextra
CC = gcc

all: s21_cat

s21_cat: s21_cat.o
	$(CC) $(CFLAGS) $< -o $@

s21_cat.o: s21_cat.c
	$(CC) -Wall -c $< -o $@ 

clean:
	rm -rf *.o s21_cat

rebuild: clean all