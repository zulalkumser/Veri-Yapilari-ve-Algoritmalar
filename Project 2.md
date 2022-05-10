# Merge Sort
**[16,21,11,8,12,22]**
---
### 1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Diziyi her adımda ikiye bölüyoruz. Daha sonra sıralıyoruz.
- **1. adım:** [16, 21, 11] , [8, 12, 22]
- **2. adım:** [16] , [21, 11] , [8, 12] , [22]
-  **3. adım:** [16] , [21] , [11] , [8] , [12] , [22]
- **4. adım:** [16] , [11, 21], [8 , 12] , [22]
-  **5.adım:** [11, 16, 21] , [8, 12, 22]
-  **6.adım:** [8, 11, 12, 16, 21, 22]

### 2. -   Big-O gösterimini yazınız.
O(nlogn)

