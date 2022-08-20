# Binary-Search-Tree 

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

Başlangıç karakterimiz 7 olarak alınır.

                        7

Ardından 5 karakterine bakılır.5<7 olduğu için 5, 7'nin soluna yazılır.

                        7
                  ↙    
            5

Sıra 3. karakter olan 1' e gelir. 1 7 den küçüktür bu sebeple soluna yazılacaktır.Fakat 7'nin solunda 5 vardır bu sebeple 1 sayısında 5 için tekrar bakılır 1 5'ten de küçük olduğu için 5 in soluna yazılır.

                        7
                  ↙      
            5
          ↙
        1

8>7 bu sebeple sağa yazılır.

                        7
                   ↙         ↘
            5                      8
          ↙                         
        1

3<7, 3<5 , 3>1 kurallarına uygun şekilde yazılır.

                        7
                   ↙         ↘
            5                      8
          ↙                        
        1
          ↘
            3

6<7, 6>5 

                        7
                  ↙          ↘
            5                      8
          ↙   ↘                    
        1       6
          ↘
            3

0<7, 0<5, 0<1 

                        7
                  ↙           ↘
            5                      8
          ↙  ↘                      
        1       6
       ↙ ↘       
      0   3

9>7, 9>8 

                        7
                   ↙         ↘
            5                    8 
          ↙   ↘                    ↘
        1      6                     9
       ↙ ↘                             
      0   3

4<7 , 4<5 ,4>1 ,4>3

                            
                        7
                  ↙           ↘
            5                      8
          ↙   ↘                      ↘
        1       6                      9
       ↙ ↘                             
      0    3
             ↘
              4
2<7, 2<5 ,2>1 ,2<3      

                        7
                  ↙            ↘ 
            5                       8
          ↙   ↘                       ↘
        1       6                       9
       ↙ ↘                              
      0   3
         ↙ ↘
        2   4