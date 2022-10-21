# patika.merge.sort.project
project 2

[16,21,11,8,12,22] dizisinin merge sort türüne göre aşamaları;

[16,21,11,8,12,22]
[16,21,11]  [8,12,22]
[16] [21,11]  [8] [12,22]
[16] [11,21]  [8] [12,22]
[11,16,21]  [8,12,22]
[8,11,12,16,21,22]

big-O gösterimi;
O(n)
2^x=n
log(2^x)=logn
x=logn ->O(n) kere
=O(nlogn)
