how to compile with running script:

$ cat lab7.script
�R�O�Z�Ұʩ� 2016�~05��31�� �W�� 11:45:58

Administrator@H64B /cygdrive/d/Jessie/�{�]/lab7
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

Administrator@H64B /cygdrive/d/Jessie/�{�]/lab7
$ ./tetris
0000
0100
0100
0110

Administrator@H64B /cygdrive/d/Jessie/�{�]/lab7
$ ./tetris
0000
0000
0110
0011

Administrator@H64B /cygdrive/d/Jessie/�{�]/lab7
$ ./tetris
0000
0100
0110
0100

Administrator@H64B /cygdrive/d/Jessie/�{�]/lab7
$ ./tetris
0010
0010
0010
0010

Administrator@H64B /cygdrive/d/Jessie/�{�]/lab7
$ exit

�R�O�Z�w�� 2016�~05��31�� �W�� 11:46:31
 ����
