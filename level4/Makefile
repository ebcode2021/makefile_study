CC = gcc
CFLAGS = -c -o

AR = ar
ARFLAGS = -rc

TARGET = libft.a

SRCS = first.c second.c third.c
OBJS = first.o second.o third.o

$(OBJS): $(SRCS)
	$(CC) $(CFLAGS) $@ $<

$(TARGET) : $(OBJS)
	$(AR) $(ARFLAGS) $@ $?