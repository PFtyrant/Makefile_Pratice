#<target>:<prerequsite> 
#	receipe

var_doller= $
var_two_dollers=$$

var1=hello1
var2=hello2
var3=hello3
a=a1
b=b1

# food: hamburger.o main.o
# 	$(CC) -o food hamburger.o main.o

# hamburger.o: hamburger.c
# 	$(CC) $(CFLAGS) hamburger.o hamburger.c
# main.o: main.c
# 	$(CC) $(CFLAGS) main.o main.c

print:
#@는 과정을 출력하지 않고, 결과 값만을 출력한다는 뜻.

# with @
# var_doller: $
# var_two_dollers: $

# without @
# echo var_doller: $
# var_doller: $
# echo var_two_dollers: $
# var_two_dollers: $
	@echo var_doller: $(var_doller)
	@echo var_two_dollers: $(var_two_dollers)
	@echo $(var1)${var2}${var3}
#    권장되지는 않는 사용법, 자동 변수(Automatic Variable)와 함께 사용될 경우 혼란을 초래할 수 있기 때문.
	@echo $a$b


clean:
	rm -rf food
	rm -rf *.o