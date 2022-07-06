NAME = libft.a

CC = gcc
CFLAGS = -Wall -Wextra -Werror

AR = ar
ARFLAGS = -rc

SRCS = first.c second.c third.c
OBJS = first.o second.o third.o

all : $(NAME)

#$(OBJS): $(SRCS)
#	$(CC) $(CFLAGS) -c $(SRCS)

%.o : %.c
	$(CC) $(CFLAGS) -c $<

$(NAME) : $(OBJS)
	$(AR) $(ARFLAGS) $@ $?