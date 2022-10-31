# 3_Binary_Search_Tree_Projesi
www.patika.dev ile Yazılıma Başlangıç Programı 

Proje 3- Binary Search Tree Projesi

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

3.1.
Dizinin root elemanı 5 olarak seçilir. (Daha düzenli, eşit bir dağılım olması açısından bu şekilde şeçmek istedim.) Her adımda rootun kendisinden küçük sayılar sol tarafına, 
kendisinden büyük sayılar da büyükler sağ tarafına gelecek şekilde yerleştirilir.
            
                         5 
                    /        \
                   3          7  
                  / \        / \ 
                 1   4      6   8        
                / \              \     
               0   2              9       

Ağacımıza baktığımızda sol tarafda roottan küçük 3,4,1,0 ve 2 sayılarını görebiliriz.
Sağ tarafta da roottan büyük 7,6,8, ve 9 sayıları yerleşmiş bulunuyor.
