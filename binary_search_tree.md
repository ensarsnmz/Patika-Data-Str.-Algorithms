# [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

1. Root olarak arrayin ilk elemanı olan 7'yi seçiyoruz.

2. Array üzerindeki elemanları sırayla tree yapımıza yerleştireceğiz. Bu adımda arrayin 1. indexindeki 5 sayısıyla devam ediyoruz. 5 7'den küçük olduğu için yeni düğümümüzü sol tarafa konumluyoruz. 
                    7
                  /
                5

3. Sıradaki elemanımız 1! 1 7'den küçük olduğu için  sol düğümde konumlanması gerekli. Sol düğümümüzde 5 sayısı hali hazırda olduğu için aynı kontrolü burada da gerçekleştiriyoruz. 1 5'ten küçük olduğu için 5'in sol düğümüne 1 sayısını yerleştiriyoruz.
                    7
                  /
                5
              /
            1

4. Sıradaki elemanımız 8! 8 7'den büyük olduğu için sağ düğüme 8 sayısını yerleştiriyoruz.
                      7
                  /       \
                5           8
              /
            1

5. Mantığı kavradığımıza göre bundan sonraki adımları kolayca halledebiliriz.
                      7
                  /       \
                5           8
              /
            1
              \
                3
        

6. 
                      7
                  /       \
                5           8
              /   \
            1      6 
              \
                3

7. 
                      7
                  /       \
                5           8
              /   \
            1      6 
          /    \
        0        3

8. 
                      7
                  /       \
                5           8
              /   \           \
            1      6            9
          /    \
        0        3
    
9. 
                      7
                  /       \
                5           8
              /   \           \
            1      6            9
          /    \
        0        3
                   \
                     4

10. 
                      7
                  /       \
                5           8
              /   \           \
            1      6            9
          /    \
        0        3
               /   \
             2       4

[patika.dev Profilim](https://app.patika.dev/ensarsnmz)