all : libft.a

*.o : *.c
	gcc -c -o *.o *.c

libft.a : first.o second.o third.o
	ar -rc libft.a *.o 

.PHONY : all

## obejct file이 없을경우 컴파일 과정에서 만들어주므로 *.o : *.c 과정은 생략 가능
## (주의) norminette에 걸린다는 이야기가 있음
