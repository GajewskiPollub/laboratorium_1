Punkt 1.
docker build -t <nazwa-obrazu> .  
![](punkt_1_1.jpg)
Punkt 2.
docker run -p 8080:8080 <nazwa-obrazu> (należy pamiętać, żeby podać tę samą nazwę obrazu, którą nadaliśmy w poprzednim kroku) 
![](punkt_2_1.jpg)
Natępnie wpisujemy w przeglądarkę adres http://localhost:8080/ w celu wyświetlenia stworzonego pliku index.php 
![](punkt_2_2.jpg)
Punkt 3.
docker exec <id_kontenera> cat /app/log.txt  
![](punkt_3_1.jpg)
Id kontenera możemy sprawdzić wpisując w konsolę polecenie docker ps 
![](punkt_3_2.jpg)
Punkt 4.
docker image inspect <nazwa_obrazu>. 
![](punkt_4_1.jpg)
Zbudowany obraz posiada 12 warstw.
