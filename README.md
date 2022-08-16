# Merge-Sort-Project
Ödev:
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

ÇÖZÜM:
1. [16,21,11] [8,12,22]
2. [16,21] [11] [8] [12,22]
3. [16] [21] [11] [8][ 12] [22]

4. [16,21][11][8][12,22]
5. [11,16,21][8,12,22]
6. [8,11,12,16,21,22]

Ağaçlama yöntemi ile gösterecek olursak:

  [16,21,11,8,12,22]
   /     /   \     \
 [16,21] [11] [8] [12,22]
 /   \    |    |   \   \ 
[16] [21] [11] [8] [12] [22]


[16] [21] [11] [8] [12] [22]
  \    /   |    |    \  /
  [16,21] [11] [8] [12,22]
      \    /     \     /
    [11,16,21]  [8,12,22]
          \        /
      [8,11,12,16,21,22] 


Big-O Gösterimi:
n=6
Best case    : O(n*logn)
Average case : O(n*logn)
Worst case   : O(n*logn) -> O(6*log6)

Patika.dev Profile: https://app.patika.dev/birgulyuksel
