# 자동 변수(Automatic variables)
# : $ 뒤에 특수기호가 붙는 것으로, 패턴룰(Pattern Rule)이라고 보면 됨
AR = AR
ARFLAGS = -rc

TARGET = libft.a

SRCS = first.c second.c third.c
OBJS = first.o second.o third.o

# $^ 대신에 $? 쓸 수 있음
# 차이 : ^는 의존하는 대상들의 전체 목록, ?는 의존하는 대상들 중 변경된 것들의 목록
$(TARGET) : $(OBJS)
	$(AR) $(ARFLAGS) $@ $^
