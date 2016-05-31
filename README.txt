how to compile with running script:

$ cat lab7.script
命令稿啟動於 2016年05月31日 上午 11:45:58

Administrator@H64B /cygdrive/d/Jessie/程設/lab7
$ make
g++ -c tetris.cpp
g++ -c genMino.cpp
g++ -c MinoL.cpp
g++ -c MinoI.cpp
g++ -c MinoS.cpp
g++ -c MinoT.cpp
g++ -c MinoZ.cpp
g++ -c Mino.cpp
g++ -o tetris tetris.o genMino.o MinoL.o MinoI.o MinoS.o MinoT.o MinoZ.o Mino.o

Administrator@H64B /cygdrive/d/Jessie/程設/lab7
$ ./tetris
0000
0100
0100
0110

Administrator@H64B /cygdrive/d/Jessie/程設/lab7
$ ./tetris
0000
0000
0110
0011

Administrator@H64B /cygdrive/d/Jessie/程設/lab7
$ ./tetris
0000
0100
0110
0100

Administrator@H64B /cygdrive/d/Jessie/程設/lab7
$ ./tetris
0010
0010
0010
0010

Administrator@H64B /cygdrive/d/Jessie/程設/lab7
$ exit

命令稿已於 2016年05月31日 上午 11:46:31
 完成
