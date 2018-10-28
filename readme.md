init
as --32 -o callee.o callee.s
yum install glibc-devel.i686 libstdc++-devel.i686
gcc -m32 -o caller caller.c callee.o
