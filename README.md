# Binary-search

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.


    Root 5 seçersek;
    sağında olanlar :[7,6,8,9] Bu dizi için tekrar root seçelim. root= 8 olsun Sağında: [9] , solunda: [7,6] en son ikili dizi için tekrar root seçilir.
                     root= 6 için [7] ve [6] olur.
    solunda olanlar : [1,3,0,2,4] Bu dizi için tekrar root seçelim. Root = 3 olsun. sağında: [4] , solunda: [1,2,0]  son dizi üçlü olduğu için tekrar root seçilir. r                          root=2 için sağında: [2] ve [1,0] olur. [1,0] dizisi için de root= 1 olsun: sağında :[1] , solunda: [0] olur.
    
    
    
    
     
      
