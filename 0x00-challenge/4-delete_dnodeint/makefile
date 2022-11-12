CC = gcc
CFLAGS = -Wall -pedantic -Werror -Wextra -std=gnu89
NAME = delete_dnodeint
SRC = main.c free_dlistint.c print_dlistint.c add_dnodeint_end.c delete_dnodeint_at_index.c
OBJ = $(SRC:.c=.o)
RM = rm -f

all: $(OBJ)
	$(CC) $(CFLAGS) $(OBJ) -o $(NAME)

clean:
	$(RM) $(OBJ) $(NAME)

re: clean all

