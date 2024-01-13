# target : hello
# prerequsite : main.c
# rules : gcc -p hello main.
# 만약 make 진행시 hello 라는 타겟을 지정하지 않은 경우, make 진행시 첫번째 타겟이 실행이 되게 된다.
# prerequsite(main.c)을 지정, 만약 마지막 make이후 target이 수정되지 않았다면, 실행되지 않는다.
hello: main.c
	gcc -o hello main.c