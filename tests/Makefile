##
## EPITECH PROJECT, 2017
## Makefile
## File description:
## makefile
##

INCLUDE		=	-I ./include

CXXFLAGS	=	$(INCLUDE) -W -Wall -Wextra -Wshadow 

CXX			=	g++

SRC_PATH	=	src/

SRC_FILES	=	main.cpp

SRC		=	$(addprefix $(SRC_PATH),$(SRC_FILES))

OBJ	=	$(SRC:.cpp=.o)

NAME	=	Indie

.SILENT:

$(NAME):	clean $(OBJ)
	$(CXX) -o $(NAME) $(OBJ) $(INCLUDE)
		@echo make

all:	$(NAME)

clean:
	rm -f $(OBJ)
		@echo clean

fclean: clean
	rm -f $(NAME)
		@echo fclean

re:	fclean all
		@echo RE

tests_run:
	make -C tests/

.PHONY: clean fclean re all tests_run
