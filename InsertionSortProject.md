# InsertionSortProject

Project 1

\*\*Task 1:

1. [22, 27, 16, 2, 18, 6] dizisini Insertion Sort ile kücükten büyüge siralayalim.
2. Big-O gösterimini yazin.
3. Dizi siralandiktan sonra 18 sayisi hangi Case kapsamina girer?Yazin.

1.Adim : Diziyi Sirala >> [22, 27, 16, 2, 18, 6] dizisi kücükten büyüge dogru siralanacaktir.

a.[22] | [27, 16, 2, 18, 6] buradan sag taraftaki diziden ilk eleman(27) alinir ve soldakiyle karsilastirilir ve siralanir.  
 b.[22, 27] | [16, 2, 18, 6] burada sag diziden "16" alinir ve sag tarafta siralanir.(16 < 22 < 27)  
 c.[16, 22, 27] | [2, 18, 6] sagdaki ilk eleman "2" alinir ve sag tarafta siralanir.(2 < 16 < 22 < 27)  
 d.[2, 16, 22, 27] | [18, 6] sagdaki ilk eleman "18" alinir ve sag tarafta siralnir.(2 < 16 < 18 < 22 < 27)  
 e.[2, 16, 18, 22, 27] | [6] sagdaki eleman alinir ve sagdaki dizide dogru yerine konur.  
 f.[2, 6, 16, 18, 22, 27] seklinde Insertion Sort ile dizi kücükten büyüge dogru siralanmis olur.

2.Adim : Big-O gösterimi

> > Diziyi siralarken eleman sayisi her seferinde 2`ye ayriliyor.Böylece "n" tane eleman var dersek x = n^2 olur.  
> > Buradan da "O(n^2)" Big-O(zaman karmasikligi) bulmus oluruz.

3.Adim : 18 sayisinin Case`ni bulma

> > "18" sayisi ne en basta ne de en sonda bulunan bir elemandi.Bu yüzden Average-Case kapsamina girer.

\*\*Task 2: 1.[7, 3, 5, 8, 2, 9, 4, 15, 6] dizisini Selection Sort`a göre ilk 4 adimini yazin.

> > \*\*Selection Sort`ta dizi bastan sona dogru taranir ve her adimda en kücük veya en büyük eleman secilip siralanacak kismin
> > basina konur.

--> Dizinin kücükten büyüge siralayalim.Ilk 4 adim:  
1.Adim: en kücük eleman "2" >> [2, 7, 3, 5, 8, 9, 4, 15, 6]  
2.Adim: en kücük eleman "3" >> [2, 3, 7, 5, 8, 9, 4, 15, 6]  
3.Adim: en kücük eleman "4" >> [2, 3, 4, 7, 5, 8, 9, 15, 6]  
4.Adim: en kücük eleman "5" >> [2, 3, 4, 5, 7, 8, 9, 15, 6]
