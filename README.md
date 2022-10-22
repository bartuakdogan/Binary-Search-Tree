# Binary-Search-Tree
patika.dev Binary Search Tree Projesi
[Patika.dev](https://www.patika.dev/tr)

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisini soldan okumaya başlıyoruz.
Eğer okuduğumuz sayı bir önceki sayıdan büyükse sayının sağına doğru küçükse soluna doğru ilerliyoruz.

7
  7
 /
5
    7
   /
  5
 /
1 
    7
   / \
  5   8
 /
1 
    7
   / \
  5   8
 / 
1  
 \
  3
    7
   / \
  5   8
 / \
1   6
 \
  3
      7
     / \
    5   8
   / \
  1   6
 / \
0   3
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
     \
      4
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
   / \
  2   4