# Binary-Search-Tree

### Project 3 ###
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

### ANSWER ###
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] Dizi içerisinde soldan sağa doğru sıra ile gidiyoruz.

#### 1. adım
Root is 7.

         7
       
#### 2. adım
5 , 7'den küçük. sol kısma yazılır.

         7
        /   
       5     

#### 3. adım
1 sayısı 7 ve 5'ten küçük 

         7
        /   
       5     
      /      
     1        
    
#### 4. adım
8 sayısı 7'den büyük, bu yüzden sağa yazılıyor

          7
        /   \
       5     8
      /      
     1    
    
#### 5. adım
3 sayısı 7 ve 5'ten küçük fakat 1'den büyük

          7
        /   \
       5     8
      /      
     1  
      \
       3
       
#### 6. adım
6 sayısı 7'den küçük ama 5'ten büyük    
       
         7
       /   \
      5     8
     /  \    
    1    6
      \
       3
       
#### 7. adım
0 sayısı hepsinden küçük

           7
         /   \
        5     8
       / \     
      1   6       
     /  \ 
    0    3
  
#### 8. adım
9 sayısı 7 ve 8'den büyük

           7
         /   \
        5     8
       / \     \
      1   6     9  
     /  \
    0    3
  
#### 9. adım
4 is smaller than 7 and 5 but greater than 3.

           7
         /   \
        5     8
       / \     \
      1   6     9  
     /  \
    0    3
          \
           4
          
#### Son adım

           7
         /   \
        5     8
       / \     \
      1   6     9  
     /  \
    0    3
        /  \
        2   4


# Binary-Sort-tree
