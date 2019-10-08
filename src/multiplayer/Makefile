##
## EPITECH PROJECT, 2017
## Makefile
## File description:
## test makefile multi indie
##

CC	=	g++

SRC	=	Server.cpp	\
		main.cpp

OBJ	=	$(SRC:.cpp=.o)

NAME	=	test

CFLAGS	=	-W -Wall -Werror

all:	$(NAME)

$(NAME):	$(OBJ)
	$(CC) -o $(NAME) $(OBJ)

clean:
	rm -f $(OBJ)

fclean:	clean
	rm -f $(NAME)

re:	fclean all

.phony: all clean fclean re
