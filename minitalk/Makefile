# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: mehmyild <mehmyild@student.42kocaeli.co    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2023/08/28 21:01:27 by mehmyild          #+#    #+#              #
#    Updated: 2023/08/31 01:39:31 by mehmyild         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME_C = client
NAME_S = server
FLAGS = -Wall -Wextra -Werror
FILE1 = client.c 
FILE2 = server.c
CC = gcc
RM = rm -rf

all: $(NAME_C) $(NAME_S)

$(NAME_C):
	@$(CC) $(FLAGS) $(FILE1) -o $(NAME_C) 

$(NAME_S):
	@$(CC) $(FLAGS) $(FILE2) -o $(NAME_S)
 
clean:
	@$(RM) $(NAME_C) $(NAME_S)

fclean: clean

re: clean all

.PHONY: all clean fclean re