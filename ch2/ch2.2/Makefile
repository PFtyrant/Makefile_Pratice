#<target>:<prerequsite> 
#	receipe
# 암시적 규칙. 명시적으로 무엇을 컴파일 할것을 지정하지 않아도
# Makefile은 자동으로 대등되는 파일 이름을 찾아 컴파일을 실행한다.
# 혹은 아예 규칙을 쓰지 않아도 된다. Implicit Rule 

# cc 는 시스템상에서 softlink로 연결된 컴파일러이다.
# 따라가다보면 gcc로 연결이 된게 보일것이다. 보통 gcc로 
# 연결이 되어 있기 때문

# *.c 파일을 가지고 cc컴파일러로 *.o를 생성하는 규칙
# *.s 파일을 가지고 as컴파일러로 *.o를 생성하는 규칙
# *.p 파일을 가지고 pc컴파일러로 *.o를 생성하는 규칙

# 아래 코멘트된 예제에서는 hamburger.o main.o를 만났으나,
# hamburger.o main.o 의 타겟이 없으므로 암시적 규칙을 사용해
# 컴파일을 진행하게 된다.
# food: hamburger.o main.o
# 	gcc -o food hamburger.o main.o

# output
# cc    -c -o hamburger.o hamburger.c
# cc    -c -o main.o main.c
# gcc -o food hamburger.o main.o


food: hamburger.o main.o
	gcc -o food hamburger.o main.o

hamburger.o: hamburger.c
main.o: main.c

clean:
	rm -rf food
	rm -rf *.o