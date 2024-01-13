Makefile은
	Makefile, makefile, GNUMakefile 
이 세가지 파일명만을 찾는다, 만약 이 세가지가 존재 하지 않는다면 make는 Makefile이 없는것으로 간주한다.
하지만 정말로 이 세가지말고 다른 파일명을 사용 하고 싶다면 "-f" 옵션을 사용하면 된다.
make -f <file name>
